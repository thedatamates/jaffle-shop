# Macro Commands - Jaffle Shop Setup

This file contains the essential commands for setting up and running dbt in this project.

## Initial Setup (One-time)

Create and activate virtual environment:
```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## Daily Development

Activate virtual environment (run this in each new terminal session):
```bash
source .venv/bin/activate
```

## dbt Commands

Once your virtual environment is activated, you can run these dbt commands:

### Essential Commands
```bash
# Install dbt packages
dbt deps

# Load seed data (first time setup)
dbt seed --full-refresh --vars '{"load_source_data": true}'

# Build all models
dbt build

# Run models only
dbt run

# Run tests only
dbt test

# Check for compilation errors
dbt compile
```

### Development Commands
```bash
# Run specific model
dbt run --select model_name

# Run models downstream from a specific model
dbt run --select model_name+

# Run models upstream from a specific model  
dbt run --select +model_name

# Run tests for specific model
dbt test --select model_name

# Check dbt version
dbt --version
```

## Notes

- Always activate the virtual environment before running dbt commands
- The typing-extensions version in requirements.txt has been updated to resolve compatibility issues
- Use `dbt --help` for full command reference