# Demo Custom Actions

This repository simulates a private organization's reusable GitHub Actions (like `emisgroup/exa-actions`).

## Available Actions

### checkout
Custom checkout action with additional features for the organization.

### setup-node
Custom Node.js setup with organization-specific configurations.

### deploy
Deployment action for organization's infrastructure.

## Usage

```yaml
# In your workflow file:
uses: YOUR_ORG/demo-custom-actions/checkout@main
uses: YOUR_ORG/demo-custom-actions/setup-node@main
uses: YOUR_ORG/demo-custom-actions/deploy@main
```

## Note
This is a demo repository for testing the action-version-updater tool.
