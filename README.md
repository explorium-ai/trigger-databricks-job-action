# Package Helm GHCR Action

Package a helm chart and deploy to an GHCR repository using OCI
## Full Example usage

```yaml
- name: Trigger a Databricks Workflow Job
  uses: explorium-ai/trigger-databricks-job-action@main
  with:
    token: fadsfads********
    host: https://abc-123fvd34-34fb.cloud.databricks.com
    job-id: abcd12345
    payload: '{"config":"something"}'
```