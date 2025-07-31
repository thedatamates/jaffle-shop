# Jaffle Shop - Macro Setup Instructions

## Setting up

**Activate venv:**
```bash
source .venv/bin/activate
```

**Install dependencies:**
```bash
dbt deps
```

**Load sample data:**
```bash
dbt seed --full-refresh --vars '{"load_source_data": true}'
```

## Rebuilding the project

**Activate venv (if not already):**
```bash
source .venv/bin/activate
```

**Build all models:**
```bash
dbt build
```

**Build specific models:**
```bash
dbt build --select <model_name>
```

### Issue information
```bash
# List issues assigned to me
gh issue list --assignee @me

# View specific issue details
gh issue view <issue-number>
```

### Creating pull requests
```bash
# Create a new branch and switch to it
git checkout -b feature/your-feature-name

# Stage and commit your changes
git add .
git commit -m "Your commit message"

# Push branch to remote first
git push origin feature/your-feature-name

# Then create PR
gh pr create --title "Your PR Title" --body "Description of changes"

# View PR status
gh pr status
```
