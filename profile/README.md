
# ripmarkus

A DevOps project built at EK, modernizing a legacy Python 2 search engine into a production-grade Ruby/Sinatra application with full CI/CD and monitoring.

Visit our documentation [here](https://ripmarkus.github.io/whoknows_ripmarkus/)

---

## The Stack

| Layer | Technology |
|---|---|
| Application | Ruby, Sinatra, PostgreSQL |
| Containerization | Docker, Docker Compose |
| CI/CD | GitHub Actions |
| Monitoring | Prometheus, Grafana |
| Infrastructure | Terraform, Hetzner Cloud |
| Target orchestration | Kubernetes (Talos Linux) |

---

## Repositories

**[whoknows_ripmarkus](https://github.com/ripmarkus/whoknows_ripmarkus)** — The main application. Ruby/Sinatra with PostgreSQL, CI/CD, RSpec tests, RuboCop, and Docker-based deployment.

**[whoknows_monitoring](https://github.com/ripmarkus/whoknows_monitoring)** — Prometheus and Grafana stack running on a separate Hetzner VPS, monitoring HTTP, business metrics and security signals.

**[whoknows_infra](https://github.com/ripmarkus/whoknows_infra)** — Terraform-provisioned Kubernetes cluster on Hetzner Cloud running Talos Linux, with a private network and load balancer as the only public entry point.
