# Jaffle Shop - Macro Setup Instructions

## Development Environment Setup

### 1. Activate Virtual Environment
```bash
source .venv/bin/activate
```

### 2. Database Connection
The project is configured to use PostgreSQL with settings defined in `profiles.yml`. The profile uses:
- Target: `dev` 
- Database: `jaffle_shop_development`
- Schema: `public`

### 3. Essential dbt Commands

**Install dependencies:**
```bash
dbt deps
```

**Load sample data:**
```bash
dbt seed --full-refresh --vars '{"load_source_data": true}'
```

**Build all models:**
```bash
dbt build
```

**Run specific tests:**
```bash
dbt test --select <test_name>
```

**Build specific models:**
```bash
dbt build --select <model_name>
```

### 4. Key Project Structure
- **Models**: `models/staging/` (views) and `models/marts/` (tables)
- **Data Tests**: `data-tests/` for custom SQL data test files (configured in dbt_project.yml)
- **Seeds**: `seeds/jaffle-data/` for sample CSV data
- **Compiled**: `target/compiled/` for compiled SQL

### 5. Linting & Type Checking
```bash
# Add lint/typecheck commands here when identified
# Example: dbt parse (for syntax checking)
```

### 6. GitHub CLI - Creating Pull Requests
```bash
# Create a new branch and switch to it
git checkout -b feature/your-feature-name

# Stage and commit your changes
git add .
git commit -m "Your commit message"

# Push branch and create PR in one command
gh pr create --title "Your PR Title" --body "Description of changes"

# View PR status
gh pr status
```

### 7. GitHub Issues Management
```bash
# List all open issues
gh issue list

# List all issues (open and closed)
gh issue list --state all

# List issues assigned to me
gh issue list --assignee @me

# View specific issue details
gh issue view <issue-number>
```

## Quick Start Commands
```bash
# Activate environment and run full build
source .venv/bin/activate && dbt build

# Run tests only
source .venv/bin/activate && dbt test

# Run specific model
source .venv/bin/activate && dbt build --select customers
```
