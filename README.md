# Report Pending Github Health Check Status

Updates the Github health status for a given pull request to pending

## How to use this Step

Add the following to your `bitrise.yml`

```
- git::https://github.com/hmrc/bitrise-step-report-pending-gitub-health-status.git@main:
    title: Report Pending Github Health Check Status
    is_always_run: true
```