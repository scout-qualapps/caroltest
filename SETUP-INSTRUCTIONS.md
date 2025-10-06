# Repository Setup Instructions

## GitHub Workflow Setup Required

A GitHub Actions workflow has been prepared for this repository, but due to API restrictions, it needs to be moved to the correct location manually.

### Steps to activate the workflow:

1. **Go to your repository**: [https://github.com/scout-qualapps/caroltest](https://github.com/scout-qualapps/caroltest)

2. **Find the workflow file**: Click on `.github/workflows/workflow.yml` in the repository root

3. **Edit the file**: Click the pencil icon (✏️) to edit

4. **Change the file path**: 
   - Change the filename from `.github/workflows/workflow.yml` 
   - To: `.github/workflows/workflow.yml`
   - GitHub will automatically create the `.github/workflows/` directory

5. **Commit the change**: 
   - Add a commit message like "Move workflow to .github/workflows/"
   - Click "Commit changes"

6. **Verify**: The workflow will now appear in the "Actions" tab of your repository


## DBT Template Files

The following DBT template files have been added to your repository in the `dbt/` folder:

### Successfully Added (15 files):
- `dbt/.gitignore`
- `dbt/Dockerfile`
- `dbt/README.md`
- `dbt/dbt_project.yml`
- `dbt/schema.yml`
- `dbt/analyses/.gitkeep`
- `dbt/macros/.gitkeep`
- `dbt/models/datamart/model_dm.sql`
- `dbt/models/intermediate/model_interm.sql`
- `dbt/models/staging/model_stg.sql`
- `dbt/profiles/.user.yml`
- `dbt/profiles/profiles.yml`
- `dbt/seeds/.gitkeep`
- `dbt/snapshots/.gitkeep`
- `dbt/tests/.gitkeep`

### Why this step is needed:

GitHub has security restrictions that prevent API-based creation of `.github` directories and workflow files. This is a common limitation when automating repository setup.

---

*This repository was created automatically. Once you complete the workflow setup above, you can delete this README if desired.*
