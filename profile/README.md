<div align="center">
  <img src="https://raw.githubusercontent.com/wiki/opswarden-git/opswarden/assets/opswarden-ops/heroicon.png" alt="OpsWarden" width="112" />
  <h1>OpsWarden</h1>
  <p>Incident response and release coordination for technical teams.</p>
  <p>
    <a href="https://opswarden.dev/">Website</a> ·
    <a href="https://app.opswarden.dev/en/login">Web application</a> ·
    <a href="https://opswarden-git.github.io/opswarden/">Documentation</a> ·
    <a href="https://github.com/opswarden-git/opswarden/releases/latest">Desktop releases</a>
  </p>
</div>

OpsWarden turns operational signals into a shared response workflow. Teams can
triage Incidents in a real-time War Room, coordinate ordered Releases and use
server-owned Action→REAction rules to connect GitHub, GitLab, Alertmanager,
Generic Webhooks, HTTP, email and timers.

## Repositories

| Repository                                                                | Responsibility                                                                             |
| ------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------ |
| [`opswarden`](https://github.com/opswarden-git/opswarden)                 | Rust/Axum server, Next.js web client, Tauri desktop client and canonical product contracts |
| [`opswarden-ops`](https://github.com/opswarden-git/opswarden-ops)         | Terraform, Kubernetes, production deployment, backups and observability                    |
| [`opswarden-website`](https://github.com/opswarden-git/opswarden-website) | Public marketing website deployed at [opswarden.dev](https://opswarden.dev/)               |

The [technical portal](https://opswarden-git.github.io/opswarden/) publishes
architecture, REST and WebSocket contracts, contributor guidance and a
source-derived inventory of the running product.

OpsWarden is available under the Apache License 2.0.
