# Awesome-Continuous-Integration-Delivery-Integrations

## Top Continuous Integration & Delivery Integrations Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on CI/CD Pipeline Automation, Build Orchestration & Deployment Integrations*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Continuous Integration & Delivery Integrations**. These tools automate the build, test, and deployment lifecycle—connecting source control events to pipeline execution, orchestrating parallel jobs, and enforcing quality gates before code reaches production.

**Examples** include GitHub Actions, GitLab CI/CD, CircleCI, Jenkins, Travis CI, Bitbucket Pipelines, Azure Pipelines, TeamCity, Codefresh, and Argo Workflows (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted CI/CD, open-source workflow engines, and community-driven build automation—ideal for platform teams, DevOps engineers, and organizations seeking transparent, vendor-neutral pipelines without per-minute cloud billing surprises.

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[GitHub Actions](https://github.com/features/actions)** | Native CI/CD within GitHub with 20,000+ Marketplace actions. Hosted runner prices reduced up to **39%** on January 1, 2026. A **$0.002/minute cloud platform charge** applies to self-hosted runner usage from March 1, 2026 (consumes from free quota) . | Linux 2-core: ~$0.006/minute (reduced); self-hosted: $0.002/minute platform charge | **Free plan**: 2,000 minutes/month private repos; **public repos unlimited and free**; self-hosted usage consumes free quota from March 2026 . 96% of customers see no bill change . |
| **[GitLab CI/CD](https://about.gitlab.com/)** | Integrated CI/CD within GitLab with `.gitlab-ci.yml` pipelines, Auto DevOps, and Kubernetes integration. Self-hosted runners consume zero minutes on any tier . | Premium: **$29/user/month** (SaaS, annual); Ultimate: $99/user/month . Negotiated discounts of 15–30% common for multi-year commitments . | **Free tier**: 400 compute minutes/month per namespace, 5 users, unlimited self-hosted runners . |
| **[CircleCI](https://circleci.com/)** | Cloud CI/CD with orbs, Docker layer caching, and test splitting. Credits are the billing currency; 30,000 credits ≈ 3,000 Linux medium minutes . | Performance: **$15/month** base + credits; additional credits $15 per 25,000 . | **Free plan**: 30,000 credits/month, 5 active users, 5 self-hosted runners, 1 macOS concurrency; credits expire monthly . |
| **[Travis CI](https://www.travis-ci.com/)** | Cloud CI with simple `.travis.yml` configuration. Usage-based pricing with Linux build credits . | Usage Based: **$13.75/month** (420,000 Linux credits/year, 80 concurrent jobs); Unlimited: $66+/month . | Free trial available; open-source projects eligible for free OSS plan credits . |
| **[Bitbucket Pipelines](https://bitbucket.org/product/features/pipelines)** | Integrated CI/CD within Bitbucket. Self-hosted runners now have a **free tier of up to 100 basic runners per workspace**; premium runners add advanced orchestration and support . | Standard: **$3/user/month**; Premium: $6/user/month . | **Free plan**: 5 users, 50 build minutes/month; **100 free self-hosted runners** per workspace (premium runners optional) . |
| **[Azure Pipelines](https://azure.microsoft.com/en-us/products/devops/pipelines/)** | Microsoft's CI/CD service with YAML pipelines. **GitHub-hosted agents** now available with pay-as-you-go pricing: macOS Standard $0.062/min, Linux 8-core $0.022/min, Windows 8-core $0.042/min. No free tier for GitHub-hosted agents . | Microsoft-hosted: $40/month per extra parallel job; GitHub-hosted agents: pay-per-minute (no free minutes) . | **Free tier**: 1 Microsoft-hosted job with 1,800 minutes/month + 1 self-hosted job unlimited; public projects: 10 free parallel jobs . |
| **[TeamCity](https://www.jetbrains.com/teamcity/)** | JetBrains' CI server. **Professional (on-premises) is free forever** with 3 build agents and 100 build configurations. Cloud from $15/committer/month (min 3) with 24,000 build credits . | Cloud: **$15/committer/month** (min 3); Enterprise on-premises: $2,399/year . | **Professional (on-premises)**: free forever, unlimited users, 3 agents, 100 configurations; **14-day trial** for Cloud . |
| **[Codefresh](https://codefresh.io/)** | Kubernetes-native CI/CD with GitOps and Argo CD integration. Positioned for container-first workflows . | **$99/month** starting price (Software Advice) . | Free trial available; free version listed . |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Jenkins](https://github.com/jenkinsci/jenkins)** | [![Stars](https://img.shields.io/github/stars/jenkinsci/jenkins?style=social&color=white)](https://github.com/jenkinsci/jenkins/stargazers) | The most widely deployed open-source automation server (MIT). 1,800+ plugins covering virtually every tool and cloud. Self-hosted with no per-minute fees—you pay only for infrastructure and maintenance . |
| **[Argo Workflows](https://github.com/argoproj/argo-workflows)** | [![Stars](https://img.shields.io/github/stars/argoproj/argo-workflows?style=social&color=white)](https://github.com/argoproj/argo-workflows/stargazers) | Container-native workflow engine for orchestrating parallel jobs on Kubernetes (CNCF graduated). Define workflows as DAGs or steps; supports artifacts, retries, cron schedules, and a REST API. The standard for Kubernetes-native CI/CD and batch processing . |
| **[Spinnaker](https://github.com/spinnaker/spinnaker)** | [![Stars](https://img.shields.io/github/stars/spinnaker/spinnaker?style=social&color=white)](https://github.com/spinnaker/spinnaker/stargazers) | Multi-cloud continuous delivery platform for automated releases across AWS, GCP, Azure, and Kubernetes. Includes canary analysis engine comparing metrics between new and stable versions to automate release decisions . |
| **[Danger](https://github.com/danger/danger)** | [![Stars](https://img.shields.io/github/stars/danger/danger?style=social&color=white)](https://github.com/danger/danger/stargazers) | Connects with CI systems and peer review platforms to execute checks and post results. Enforces quality, security, and documentation standards before manual review . |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[continuedev/continue](https://github.com/continuedev/continue)** | [![Stars](https://img.shields.io/github/stars/continuedev/continue?style=social&color=white)](https://github.com/continuedev/continue/stargazers) | Automated code review platform integrating AI agents into the SDLC. Executes custom validation rules against pull request diffs, providing immediate feedback via repository status checks . |
| **[PHP Censor](https://github.com/php-censor/php-censor)** | [![Stars](https://img.shields.io/github/stars/php-censor/php-censor?style=social&color=white)](https://github.com/php-censor/php-censor/stargazers) | Open-source self-hosted continuous integration server for PHP projects. Lightweight alternative to Jenkins for PHP-centric teams . |
| **[CDS](https://github.com/ovh/cds)** | [![Stars](https://img.shields.io/github/stars/ovh/cds?style=social&color=white)](https://github.com/ovh/cds/stargazers) | Enterprise-grade continuous delivery and DevOps automation platform written in Go. Self-hosted with pipeline orchestration and artifact management . |

**Frameworks for building custom systems**: Combine **Jenkins** for general-purpose automation, **Argo Workflows** for Kubernetes-native pipeline orchestration, **Spinnaker** for multi-cloud continuous delivery, and **Danger** for PR-based quality gates—creating a fully self-hosted CI/CD stack without per-minute cloud billing.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- CI/CD platforms handle source code, credentials, and deployment access; enforce least-privilege runner permissions, mask secrets in logs, and isolate self-hosted runners.
- Pricing changes frequently: GitHub Actions introduced a self-hosted platform charge in March 2026, Bitbucket added a 100-runner free tier, and Azure Pipelines now offers pay-as-you-go GitHub-hosted agents with no free minutes . Always verify against vendor pricing pages before committing.

---

**Made for DevOps engineers, platform teams, and developers building automated delivery pipelines.**  
Let's make CI/CD integrations more open, automatable, and cost-predictable.
