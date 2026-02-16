# helmfile2compose

> *"Abandon all hope, yee who enter here"* — Semple

Convert Kubernetes manifests to `compose.yml` + `Caddyfile`. Not Kubernetes-in-Docker — no cluster, no kubelet, no shim. A devolution of the power of Kubernetes into the simplicity of compose. Plain `docker compose up`. Plain Caddy. Plain suffering.

## Repositories

| Repo | Purpose |
|------|---------|
| [h2c-core](https://github.com/helmfile2compose/h2c-core) | The core converter. Patient zero. |
| [h2c-manager](https://github.com/helmfile2compose/h2c-manager) | Package manager + extension registry |
| [h2c-operator-keycloak](https://github.com/helmfile2compose/h2c-operator-keycloak) | Keycloak CRD converter |
| [h2c-operator-certmanager](https://github.com/helmfile2compose/h2c-operator-certmanager) | cert-manager CRD converter |
| [h2c-operator-trust-manager](https://github.com/helmfile2compose/h2c-operator-trust-manager) | trust-manager CRD converter |

## Documentation

**[helmfile2compose.github.io](https://helmfile2compose.github.io/)** — for those who choose to proceed.

*You have been warned.*
