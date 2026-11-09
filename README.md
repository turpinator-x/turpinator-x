## Jarrod Turpin

DevOps and platform engineer in Carlsbad, California, with 20+ years in enterprise IT at Microsoft, Amazon and Boeing. I build and run my own Kubernetes platform with GitOps, I've built Azure infrastructure with Terraform in training, and I put tests, scans and approvals in front of every change. My Kubernetes and cloud work so far is on my own platform and in training, and I'm preparing for the CKA.

I'm looking for DevOps and platform engineering roles, remote or in San Diego County.

### What I run

| Project | What it is |
|---|---|
| [homelab](https://github.com/turpinator-x/homelab) | A two-node k3s cluster (amd64 and arm64) managed by FluxCD from Git: Helm and Kustomize, SOPS-encrypted secrets, Prometheus and Grafana, Renovate updates and Cloudflare Tunnels, with build docs and a troubleshooting log |
| [homelab-dashboard](https://github.com/turpinator-x/homelab-dashboard) | A live status page at [dashboard.jarrodturpin.dev](https://dashboard.jarrodturpin.dev): an AI-assisted FastAPI app shipped as a multi-arch image and deployed by Flux |
| [lab](https://github.com/turpinator-x/lab) | Coursework: Bash, Docker, Kubernetes, containerlab networking, dev containers and a Cilium sandbox |
| [cryptolighthouse.io](https://cryptolighthouse.io) | A free, non-custodial crypto toolkit on Cloudflare Workers, built with Claude Code: every wallet transaction goes through one guard function, with CI, deploys and Renovate updates I run (private repo) |

Private training and course builds, available to walk through in an interview:

- **Azure platform (training build, torn down after each phase):** staging and production AKS clusters from one Terraform module, PostgreSQL with backups and a point-in-time restore drill, and alerts to my phone.
- **CI/CD to GitOps (course project):** a pipeline from pull request to deployment, gated by linting, tests with an 80% coverage floor, Trivy image scans and end-to-end tests on k3d, with automated releases and Flux deploying from a separate GitOps repository.
- **Repository standards:** one safety baseline across my repositories: Conventional Commits, pre-commit, secret scanning, ShellCheck and Renovate.

### How I work

I use Claude Code as an AI pair programmer. I set the requirements and guardrails, review the changes, and test them myself. Projects built mainly with AI are labelled that way.

### Tools

Kubernetes (k3s, AKS, k3d) · FluxCD · Helm · Kustomize · Terraform · Microsoft Azure · GitHub Actions · Azure DevOps · Docker · Prometheus · Grafana · SOPS · Renovate · Linux · Bash · Python (scripting)

### Contact

[jarrodturpin.com](https://jarrodturpin.com) · [LinkedIn](https://www.linkedin.com/in/jarrod-turpin) · [Substack](https://blockoneglobal.substack.com) · [blockoneglobal.com](https://www.blockoneglobal.com)
