# helmfile2compose

O traveler, you who have arrived at these gates — know that the path behind you remains open. You may still turn back. None shall judge the wise who flee.

**[Documentation](https://helmfile2compose.github.io/)** — for those who choose to proceed.

### The concept

An abomination. Convert Kubernetes manifests to `compose.yml` + `Caddyfile`. Not Kubernetes-in-Docker — no cluster, no kubelet, no shim. Plain `docker compose up`, plain Caddy, plain suffering.

Three components: **h2c-core** (*the mad scribe*) converts the manifests, **extensions** (*the damned*) extend it beyond built-in kinds — CRD providers, converters, transforms, tomorrow whatever Yog Sa'rath demands — and **h2c-manager** (*the dark priest*) downloads and orchestrates everything.

> *"Abandon all hope, yee who enter here"* — Semple (allegedly)

### Repositories

| Repo | Purpose |
|------|---------|
| [h2c-core](https://github.com/helmfile2compose/h2c-core) | Bare conversion engine — empty registries, no opinions |
| [helmfile2compose](https://github.com/helmfile2compose/helmfile2compose) | The distribution — core + 8 monks. Patient zero. |
| [kubernetes2simple](https://github.com/helmfile2compose/kubernetes2simple) | Turnkey distribution — all extensions + bootstrap script |
| [h2c-manager](https://github.com/helmfile2compose/h2c-manager) | Package manager + extension registry |
| [helmfile2compose.github.io](https://github.com/helmfile2compose/helmfile2compose.github.io) | Documentation site |
| [h2c-testsuite](https://github.com/helmfile2compose/h2c-testsuite) | Regression & performance test suite |

Monks, extensions, rewriters, transforms — see the **[extension catalogue](https://helmfile2compose.github.io/catalogue/)**.
