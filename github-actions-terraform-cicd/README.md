# CI/CD pipeline bundle

Replace all `vars.*` values in GitHub Environments (`test`, `qa`, `prod`), replace `nexus.example.internal`, and review role trust policies before use.

The Lambda creation fallback requires `role_arn` and `handler` in environment YAML. Batch image steps are repository-specific placeholders because workload Docker contexts were not supplied.
