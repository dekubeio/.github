# dekube

O traveler, you who have arrived at these gates — know that the path behind you remains open. You may still turn back. None shall judge the wise who flee.

**[Documentation](https://docs.dekube.io/)** — for those who choose to proceed.

### The concept

An abomination. Convert Kubernetes manifests to `compose.yml` + `Caddyfile`. Not Kubernetes-in-Docker — no cluster, no kubelet, no shim. Plain `docker compose up`, plain Caddy, plain suffering.

Three components: **dekube-engine** (*the mad scribe*) converts the manifests, **extensions** (*the damned*) extend it beyond built-in kinds — CRD providers, converters, transforms, tomorrow whatever Yog Sa'rath demands — and **dekube-manager** (*the dark priest*) downloads and orchestrates everything.

> *"Abandon all hope, yee who enter here"* — Semple (allegedly)

### Repositories

| Repo | Purpose |
|------|---------|
| [dekube-engine](https://github.com/dekubeio/dekube-engine) | Bare conversion engine — empty registries, no opinions |
| [helmfile2compose](https://github.com/dekubeio/helmfile2compose) | The distribution — core + 8 monks. Patient zero. |
| [kubernetes2simple](https://github.com/dekubeio/kubernetes2simple) | Turnkey distribution — all extensions + bootstrap script |
| [dekube-manager](https://github.com/dekubeio/dekube-manager) | Package manager + extension registry |
| [dekube-docs](https://github.com/dekubeio/dekube-docs) | Documentation site |
| [dekube-testsuite](https://github.com/dekubeio/dekube-testsuite) | Regression & performance test suite |

Monks, extensions, rewriters, transforms — see the **[extension catalogue](https://docs.dekube.io/catalogue/)**.
