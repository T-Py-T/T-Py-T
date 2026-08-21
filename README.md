<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&duration=4000&pause=1000&color=58A6FF&center=true&vCenter=true&multiline=true&repeat=true&width=800&height=100&lines=Platform+Engineering+%7C+AI+Systems;Declarative+Infrastructure+%7C+Evaluation+Tooling" alt="Platform Engineering and AI Systems; Declarative Infrastructure and Evaluation Tooling" />
</div>

# Taylor — Platform & AI Systems

I build systems at the boundary of AI workloads, platform infrastructure, and
developer tooling. This profile is an evidence map: implementation and retained
artifacts come first, and plans, private boundaries, and historical work are
labelled explicitly.

## Primary public evidence

| Project | Engineering signal | Start here |
| --- | --- | --- |
| [`nix-homelab`](https://github.com/T-Py-T/nix-homelab) | Modular NixOS services, host profiles, GPU/AI nodes, runtime-secret boundaries, flake evaluation, and a representative NixOS VM health test. | [Architecture](https://github.com/T-Py-T/nix-homelab#at-a-glance) · [NixOS operations](https://github.com/T-Py-T/nix-homelab/blob/main/docs/nixos.md) · [VM test](https://github.com/T-Py-T/nix-homelab/blob/main/tests/miniflux-grafana.nix) |
| [`ants-strategy-agent`](https://github.com/T-Py-T/ants-strategy-agent) | A deterministic multi-agent strategy system with a local engine, sandbox, fixed opponents, replay tooling, benchmark entry points, and PR-gated tests. | [System design](https://github.com/T-Py-T/ants-strategy-agent#system-design) · [Strategy source](https://github.com/T-Py-T/ants-strategy-agent/blob/main/src/bots/bot.py) · [Evaluation contract](https://github.com/T-Py-T/ants-strategy-agent#evaluation-contract) |

## Supporting public work

| Project | What it contributes | Evidence boundary |
| --- | --- | --- |
| [`kubernetes-gitops-homelab`](https://github.com/T-Py-T/kubernetes-gitops-homelab) | Kubernetes/GitOps architecture, environment separation, reconciliation order, security boundaries, and rebuild-first recovery thinking. | Architecture case study; current cluster-specific state is private and no uptime or recovery outcome is claimed. |
| [`starcraft2-ppo-agent`](https://github.com/T-Py-T/starcraft2-ppo-agent) | Gymnasium/PPO environment, process-safe learner-to-game IPC, Protoss action layer, and headless regression tests. | The software contract is tested; convergence and competitive gameplay still require a versioned live-game evidence bundle. |
| [`gta5-vision-driving-agent`](https://github.com/T-Py-T/gta5-vision-driving-agent) | Historical pixel-to-action imitation-learning pipeline: screen capture, CNN experiments, nine-action encoding, and motion recovery. | Archived implementation study; no dataset, weights, benchmark, or gameplay-performance result is claimed. |
| [`trading-platform-orchestration`](https://github.com/T-Py-T/trading-platform-orchestration) | Compose/Kubernetes integration contract, runtime inputs, probes, resource constraints, manifest tests, and operator documentation. | Component source is private, so this public repo makes no source-verifiable latency, throughput, or full-stack behavior claim. |

## How I present engineering work

- Link architectural and behavioral claims to public source or retained evidence.
- Separate tested behavior from plans, private implementation, and historical work.
- Treat evaluation as a versioned artifact: revision, environment, commands,
  raw output, and derivation should travel together.
- Keep automation safe by default: local checks first, GitHub Actions only as a
  pull-request merge gate, and runtime credentials outside source control.
- Prefer explicit operating contracts, rollback boundaries, and failure modes
  over broad technology inventories.

Additional product-software and agent-evaluation flagships are being prepared
privately. They will replace supporting pins only after their public source,
tests, recruiter-facing evidence, and safety boundaries are complete.

More work is available in my [public repository list](https://github.com/T-Py-T?tab=repositories).
