# OpenMSP - a practical baseline for small MSPs and internal IT teams.

OpenMSP collects repeatable patterns and documentation so that small IT teams can start from a solid foundation instead of reinventing the wheel. The project favors open standards and simple tooling so that the content can be used in almost any environment.

## Philosophy
- Open standards first (e.g. OIDC, S3, Postgres, Podman, KVM/QEMU).
- Vendor-agnostic, easy to migrate or self-host.
- Documented runbooks > magic.

## Project Structure
- **docs/** – living documentation. Each subfolder maps to a capability: monitoring, backups, security baselines, ticketing flows, client documentation templates, automation starters, and training resources.

## Scope (v0)
- **Monitoring & alerts**: Prometheus/Grafana + IR playbooks
- **Backups**: policies, verification jobs, restore drills.
- **Security baselines**: Windows/Linux/M365 hardening + patch cadence.
- **Ticketing flows**: generic workflows; example SLAs/OLAs.
- **Client-ready docs**: policy templates.
- **Automation starters**: Ansible, Terraform, Kubernetes examples.
- **Training Resources**

## Getting Started
The documentation is a work in progress. Browse the [docs](docs/README.md) directory to explore available guidance. Each page is intentionally minimal and designed to be expanded with real-world lessons.

## Contributing
Contributions of any size are welcome. If you have improvements, additional runbooks, or corrections:
1. Fork the repository.
2. Make your changes in a feature branch.
3. Open a pull request describing your contribution.

## Status
_In progress_ — this repository currently provides a skeleton. Initial docs are being filled in incrementally.

## License
Released under the [MIT License](LICENSE).
