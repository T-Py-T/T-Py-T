<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&duration=4000&pause=1000&color=58A6FF&center=true&vCenter=true&multiline=true&repeat=true&width=800&height=100&lines=Platform+Engineering+%7C+AI+Systems;Declarative+Infrastructure+%7C+Evaluation+Tooling" alt="Platform Engineering and AI Systems; Declarative Infrastructure and Evaluation Tooling" />
</div>

# Hi, I'm Taylor

I build software where application development, AI systems, and infrastructure
meet. I enjoy turning complicated systems into tools that are repeatable,
observable, and straightforward for other people to run.

## Featured projects

### [nix-homelab](https://github.com/T-Py-T/nix-homelab)

A modular NixOS homelab built around reusable service modules and host profiles.
It includes GPU/AI hosts, runtime-secret boundaries, flake checks, and a NixOS
VM test for representative services.

[Overview](https://github.com/T-Py-T/nix-homelab#readme) ·
[NixOS operations](https://github.com/T-Py-T/nix-homelab/blob/main/docs/nixos.md) ·
[VM test](https://github.com/T-Py-T/nix-homelab/blob/main/tests/miniflux-grafana.nix)

### [ants-strategy-agent](https://github.com/T-Py-T/ants-strategy-agent)

A deterministic strategy bot for the Ants AI Challenge, with a local engine,
multiple bot implementations, repeatable match runners, benchmark tooling, and
a browser replay viewer.

[System design](https://github.com/T-Py-T/ants-strategy-agent#system-design) ·
[Local setup](https://github.com/T-Py-T/ants-strategy-agent#local-setup) ·
[Evaluation contract](https://github.com/T-Py-T/ants-strategy-agent#evaluation-contract)

### [kubernetes-gitops-homelab](https://github.com/T-Py-T/kubernetes-gitops-homelab)

The public architecture and operating guide for a Kubernetes homelab managed
with GitOps. Environment-specific Argo CD applications, hostnames, and secrets
remain in private downstream repositories.

[Architecture](https://github.com/T-Py-T/kubernetes-gitops-homelab#architecture) ·
[Deployment contract](https://github.com/T-Py-T/kubernetes-gitops-homelab#deployment-contract)

### [starcraft2-ppo-agent](https://github.com/T-Py-T/starcraft2-ppo-agent)

A Gymnasium environment and PPO training loop connected to a BurnySC2 Protoss
bot through a process-safe request/response protocol.

[Architecture](https://github.com/T-Py-T/starcraft2-ppo-agent#architecture) ·
[Live setup](https://github.com/T-Py-T/starcraft2-ppo-agent#live-setup)

### [trading-platform-orchestration](https://github.com/T-Py-T/trading-platform-orchestration)

Compose and Kubernetes orchestration for a componentized trading platform,
including runtime configuration, health probes, resource limits, manifest
tests, and operator documentation.

[Architecture](https://github.com/T-Py-T/trading-platform-orchestration#architecture) ·
[Operator setup](https://github.com/T-Py-T/trading-platform-orchestration#full-stack-operator-setup)

### [gta5-vision-driving-agent](https://github.com/T-Py-T/gta5-vision-driving-agent)

A legacy computer-vision experiment that learns a nine-action driving policy
from GTA V screen captures and keyboard demonstrations.

[Architecture](https://github.com/T-Py-T/gta5-vision-driving-agent#architecture) ·
[Local validation](https://github.com/T-Py-T/gta5-vision-driving-agent#local-validation)

## How I build

- Automate repeatable checks and keep the local development path documented.
- Keep credentials and environment-specific configuration out of source.
- Prefer small modules with explicit interfaces over tightly coupled systems.
- Retain useful outputs—tests, replays, diagrams, and run manifests—next to the
  code that produced them.

Browse the rest of my work in the
[repository list](https://github.com/T-Py-T?tab=repositories).
