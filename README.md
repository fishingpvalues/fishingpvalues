### Daniel Fischer

Software engineer and data scientist in Bielefeld, Germany. I build and run
LLM platforms: model selection, GPU serving on Kubernetes, RAG, agentic
workflows and the evaluation that tells you whether any of it works.

Currently at [mittwald](https://www.mittwald.de/mstudio/ai-hosting), AI Hosting.
M.Sc. Data Science (Hochschule Bielefeld), B.Sc. Economics (Universität Bielefeld).

[LinkedIn](https://www.linkedin.com/in/danielfischerbielefeld) ·
[Publications](https://github.com/fishingpvalues/papers) ·
[mittwald AI Hosting docs](https://developer.mittwald.de/docs/v2/platform/aihosting/)

#### Work

- LLM inference on 2x NVIDIA RTX PRO 6000 Blackwell with vLLM, Kubernetes,
  Helm, KEDA and the NVIDIA KAI scheduler
- Model portfolio and selection for mittwald AI Hosting, from Qwen3.5-0.8B for
  routing to 122B models, documented in the
  [developer docs](https://developer.mittwald.de/docs/v2/platform/aihosting/models/)
- Evaluation, load testing and guardrails for production LLM APIs
- Coding agents (Claude Code, Codex, pi, opencode) against self-hosted models,
  every change reviewed

#### Publications

- Fischer, D. et al. (2024). *Demystifying Reinforcement Learning in Production
  Scheduling via Explainable AI.* [arXiv:2408.09841](https://arxiv.org/abs/2408.09841)
- Schwede, C., Fischer, D. (2024). *Learning Simulation-Based Digital Twins for
  Discrete Material Flow Systems: A Review.* Winter Simulation Conference 2024.
  [doi:10.1109/WSC63780.2024.10838729](https://doi.org/10.1109/WSC63780.2024.10838729)

#### Selected projects

| Project | What it is |
|---|---|
| [simpleaudiospectral](https://github.com/fishingpvalues/simpleaudiospectral) | Self-hosted signal analysis web app; releases, CI, coverage, SBOM and SLSA provenance, multi-arch images |
| [rustypastechat](https://github.com/fishingpvalues/rustypastechat) | Android chat app (Kotlin, Material 3) with an assistant on any OpenAI-compatible endpoint; tested, released |
| [resnet-bilstm-attention-dt](https://github.com/fishingpvalues/resnet-bilstm-attention-dt) | Master's thesis code: verification and validation of simulation-based digital twins |
| [papers](https://github.com/fishingpvalues/papers) | PDFs of my publications |

#### Homelab

Two Linux servers running about 130 containerised services with Docker Compose,
kept as infrastructure as code: VictoriaMetrics, Grafana and Alertmanager for
monitoring, SOPS-encrypted secrets, access through Tailscale, encrypted
off-site backups, around 800 unit tests and pre-commit hooks. Document OCR with
self-hosted models, an AI agent with long-term memory, and a Home Assistant
smart home the agent can control through MCP. The repository is private;
happy to walk through it.
