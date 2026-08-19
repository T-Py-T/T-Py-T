<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&duration=4000&pause=1000&color=58A6FF&center=true&vCenter=true&multiline=true&repeat=true&width=800&height=100&lines=Platform+Engineering+%7C+AI+Systems;Declarative+Infrastructure+%7C+Developer+Tooling" alt="Platform Engineering and AI Systems; Declarative Infrastructure and Developer Tooling" />
</div>

# Taylor — Platform & AI Systems

I build and document systems where AI workloads, platform infrastructure, and
developer tooling meet. This profile is an evidence map: public code and
documentation come first, and work in progress is labeled as such.

## Current focus

- Reproducible host and service configuration with NixOS and flakes
- Operational foundations for AI and GPU workloads in a home-lab environment
- Clear architecture, deployment paths, and constraints for multi-service systems

## Selected public work

| Project | What the public repository shows | Status and evidence |
| --- | --- | --- |
| [nix-homelab](https://github.com/T-Py-T/nix-homelab) | A modular NixOS homelab where machines are flake outputs and services are self-contained modules selected by host profile. | **Active / evolving.** See the [repository layout](https://github.com/T-Py-T/nix-homelab#layout), [NixOS guide](https://github.com/T-Py-T/nix-homelab/blob/main/docs/nixos.md), [GPU-node guide](https://github.com/T-Py-T/nix-homelab/blob/main/docs/dgx-spark.md), and [Mac Studio guide](https://github.com/T-Py-T/nix-homelab/blob/main/docs/macos.md). |
| [AntsAIBot](https://github.com/T-Py-T/AntsAIBot) | A Python strategy bot repository with a local game engine, replay visualizer, benchmark tooling, and CI-backed tests. | **Public / maintained.** Inspect the [game-engine source](https://github.com/T-Py-T/AntsAIBot/tree/main/src/ants), [testing and evaluation commands](https://github.com/T-Py-T/AntsAIBot/blob/main/README.md#testing--evaluation), [CI workflow](https://github.com/T-Py-T/AntsAIBot/blob/main/.github/workflows/ci.yml), and [replay visualizer source](https://github.com/T-Py-T/AntsAIBot/tree/main/visualizer). This profile makes no benchmark outcome claim. |

## How I present engineering work

- Link architectural claims to public source or documentation.
- Separate implemented behavior from plans and work in progress.
- Attach performance claims to reproducible methodology and retained evidence.
- Prefer concise operational guidance over broad technology inventories.

More public work is available in my [repository list](https://github.com/T-Py-T?tab=repositories).
