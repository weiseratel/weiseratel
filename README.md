# Josué V. Herrera

Backend & platform engineer. I build financial systems in .NET and run them on Kubernetes. Based in Barcelona.

---

### What I'm building

[**Ratelbau**](https://ratelbau.com) is a financial community platform I'm building: fundamental stock analysis, markets, portfolio optimization, and trading education. The codebase is private, so here is the shape of it.

- **Backend** — a .NET 10 modular monolith, hexagonal and CQRS. Six bounded contexts, each isolated by its own PostgreSQL schema, talking over an integration-event bus (Wolverine on RabbitMQ). Any module can leave for its own pod without rewriting a handler.
- **Frontend** — Next.js 16 (App Router), React 19, TypeScript in strict mode, Tailwind v4.
- **Quant** — a Python and FastAPI microservice for portfolio optimization with skfolio (Markowitz, Black-Litterman, HRP).
- **Platform** — k3s on Hetzner, GitOps with ArgoCD, observability on Grafana Cloud. CI builds images to GHCR, an image updater writes the digest back to git, and ArgoCD reconciles the cluster.

Most of that work is private, so it shows up in my contribution activity rather than as public repositories.

---

### Tech

`.NET 10` · `C# 14` · `PostgreSQL` · `Wolverine` · `RabbitMQ` · `Kubernetes` · `ArgoCD` · `Next.js` · `Python`

---

### Open source

- **[sysctl](https://github.com/weiseratel/sysctl)** — Linux kernel tuning for server performance and security.
- **[yumrepomanager](https://github.com/weiseratel/yumrepomanager)** — a graphical YUM repository manager, written in C++.

---

[LinkedIn](https://www.linkedin.com/in/weiseratel) · [ratelbau.com](https://ratelbau.com)
