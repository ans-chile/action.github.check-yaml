# Check Deployment Action

## Description

This action is used to lint and check the manifest files of a deployment repository.

Additionally, check the ans helm chart and the deployment files.

## Inputs

### `chart_path`

**Required** The path to the helm chart.

## Usage

```yaml
# How to use it
uses: ans-chile/action.github.check-deployment@v1
with:
  chart_path: 'path/to/chart'
```

## Important

Don't hardcode the token in the action.yml file. Use the secrets instead.
