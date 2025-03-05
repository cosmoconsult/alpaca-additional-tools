# COSMO Alpaca additional tools

This repository contains tools which are not part of the default setup of COSMO Alpaca but might be helpful in your projects

## Included tools

### Validate linked work items for PRs
Workflow which checks if an Azure DevOps Work Item is linked to the current PR

Usage:

#### Option 1:
Copy workflow file to your repository
/.github/workflows/validate-linked-work-item.yaml

#### Option 2:
- Fork Repository to your organization
- Setup Branch policy for your default branch
- Enable "Require Workflow to pass before merging"
- Link Workflow from fork to your policy