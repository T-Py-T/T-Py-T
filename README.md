<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&duration=4000&pause=1000&color=58A6FF&center=true&vCenter=true&multiline=true&repeat=true&width=800&height=100&lines=Platform+Engineering+%7C+AI+Systems;Declarative+Infrastructure+%7C+Developer+Tooling" alt="Platform Engineering and AI Systems; Declarative Infrastructure and Developer Tooling" />
</div>

# Taylor — Platform & AI Systems

I build and document systems where AI workloads, platform infrastructure, and
developer tooling meet. This profile is an evidence map: public code and
documentation come first, and work in progress is labeled as such.

## Current focus

- Reproducible host and service configuration with NixOS and flakes
- Repeatable Kubernetes and cloud delivery through GitOps and CI/CD
- Operational foundations for AI, GPU, and multi-service workloads
- Clear architecture, validation paths, security boundaries, and recovery constraints

## Selected public work

| Project | What the public repository shows | Status and evidence |
| --- | --- | --- |
| [Kubernetes Homelab](https://github.com/T-Py-T/homelab) | A public architecture case study for rebuilding, validating, promoting, and observing a multi-environment GitOps platform while keeping live ArgoCD configuration private. | **Public / evolving.** Review the [architecture](https://github.com/T-Py-T/homelab#architecture), [deployment contract](https://github.com/T-Py-T/homelab#deployment-contract), and [platform decisions](https://github.com/T-Py-T/homelab#platform-decisions). |
| [nix-homelab](https://github.com/T-Py-T/nix-homelab) | A modular NixOS homelab where machines are flake outputs and services are self-contained modules selected by host profile. | **Active / evolving.** See the [repository layout](https://github.com/T-Py-T/nix-homelab#layout), [NixOS guide](https://github.com/T-Py-T/nix-homelab/blob/main/docs/nixos.md), [GPU-node guide](https://github.com/T-Py-T/nix-homelab/blob/main/docs/dgx-spark.md), and [Mac Studio guide](https://github.com/T-Py-T/nix-homelab/blob/main/docs/macos.md). |
| [AntsAIBot](https://github.com/T-Py-T/AntsAIBot) | A Python strategy bot repository with a local game engine, replay visualizer, benchmark tooling, and CI-backed tests. | **Public / maintained.** Inspect the [game-engine source](https://github.com/T-Py-T/AntsAIBot/tree/main/src/ants), [testing and evaluation commands](https://github.com/T-Py-T/AntsAIBot/blob/main/README.md#testing--evaluation), [CI workflow](https://github.com/T-Py-T/AntsAIBot/blob/main/.github/workflows/ci.yml), and [replay visualizer source](https://github.com/T-Py-T/AntsAIBot/tree/main/visualizer). This profile makes no benchmark outcome claim. |

## Cloud delivery case studies

These repositories use bounded application workloads to make the delivery
system inspectable. Where an upstream demo application is used, the README
separates that code from my infrastructure, CI/CD, security, and operating
work.

| Case study | Engineering question |
| --- | --- |
| [EKS + Jenkins microservices](https://github.com/T-Py-T/eks-jenkins-microservices-cicd) | How do independent service pipelines build, scan, publish, and promote a polyglot workload onto EKS? |
| [AKS + Azure DevOps microservices](https://github.com/T-Py-T/aks-ado-microservices-cicd) | How does the same workload expose different delivery and environment-promotion tradeoffs on Azure? |
| [Jenkins delivery system](https://github.com/T-Py-T/Full-Jenkins-CICD-Java-WebApp) | How do source, artifact, image, security, deployment, and observability stages form one repeatable path? |
| [Kubernetes the hard way—local lab](https://github.com/T-Py-T/kubernetes-the-hard-way) | How can control-plane bootstrap and failure diagnosis be rehearsed locally without cloud spend? |

## How I present engineering work

- Link architectural claims to public source or documentation.
- Separate implemented behavior from plans and work in progress.
- Attach performance claims to reproducible methodology and retained evidence.
- Credit upstream workloads and make my engineering boundary explicit.
- Prefer concise operational guidance over broad technology inventories.

More public work is available in my [repository list](https://github.com/T-Py-T?tab=repositories).
