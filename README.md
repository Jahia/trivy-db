# trivy-db

The official Trivy DB is hitting rate limit frequently due to a very high usage. The goal of this codebase is to make available a clone of the official repo for our own usage.

Configuration has been inspired from documentation available here: https://aquasecurity.github.io/trivy/v0.55/docs/advanced/air-gap/#offline-mode, with one workflow per OCI database.

Corresponding workflows:
 - https://github.com/aquasecurity/trivy-checks/blob/main/.github/workflows/release.yaml
 - https://github.com/aquasecurity/trivy-db/blob/main/.github/workflows/cron.yml
 - https://github.com/aquasecurity/trivy-java-db/blob/main/.github/workflows/cron.yml

