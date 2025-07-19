# Github actions PoC
- PoC for invoking a reusable workflow from another repo
- Refer to [gh-actions-poc](https://github.com/melissafilomeno/gh-actions-poc) for details of workflow processing

## Pre-requisites :
- Enable workflow permissions to GITHUB_TOKEN to create Pull Requests
  - Settings > Actions > General > Workflow permissions :
    - Enable 'Read and write permissions'
    - Check 'Allow GitHub Actions to create and approve pull requests'
   
## Verification (Manual Trigger) :
- Go to 'Actions' Tab
- Click 'Reusable workflow example' under 'Workflows'
- Click 'Run Workflow'
- Select 'Branch: main'
- Click 'Run workflow'
- Refresh page
- Latest run appears in the first entry in 'workflow runs' table
