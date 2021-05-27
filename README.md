K8S deployment for https://nioctib.tech and https://explorer.nioctib.tech using [FluxCD](https://fluxcd.io/).

Secrets is managed by [sops](https://github.com/mozilla/sops) backed by Google [KMS](https://cloud.google.com/security-key-management). FluxCD
automatically decrypt the secrets before syncing them to the Kubernetes cluster.
