# Awesome-Continuous-Integration-Delivery-Integrations

## Top Continuous Integration & Delivery Integrations Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on CI/CD Pipeline Automation, Build Orchestration & Deployment Integrations*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Continuous Integration & Delivery Integrations**. These tools automate the build, test, and deployment lifecycle—connecting source control events to pipeline execution, orchestrating parallel jobs, and enforcing quality gates before code reaches production.

**Examples** include GitHub Actions, GitLab CI/CD, CircleCI, Jenkins, Travis CI, Bitbucket Pipelines, Azure Pipelines, TeamCity, Codefresh, and Argo Workflows (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted CI/CD, open-source workflow engines, and community-driven build automation—ideal for platform teams, DevOps engineers, and organizations seeking transparent, vendor-neutral pipelines without per-minute cloud billing surprises.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global Continuous Integration & Delivery (CI/CD) and automated deployment pipeline market is valued between **$4 billion and $13 billion**, expanding rapidly at a CAGR of 15–20% fueled by cloud-native adoption and DevSecOps consolidation. The sector exhibits a distinct two-tier market structure: it is **moderately concentrated at the enterprise layer** where hyperscalers and SCM-integrated powerhouses (Microsoft/GitHub, GitLab, Atlassian) capture dominant market share through unified developer platforms, yet **highly fragmented across the broader ecosystem** with specialized niche tools, GitOps controllers, and self-hosted open-source runners tailored for custom and air-gapped infrastructure.

## SaaS/Hosted Platforms

| Product | Company Scale (Valuation / Revenue) | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|------------------------------------|-------------|-------------------|--------------------------|
| **[Azure Pipelines](https://azure.microsoft.com/en-us/products/devops/pipelines/)** | **~$3.1 Trillion** market cap (Microsoft) / **$245B+** annual revenue | Microsoft's enterprise CI/CD service with YAML pipelines. GitHub-hosted agents available with pay-as-you-go pricing (macOS Standard $0.062/min, Linux 8-core $0.022/min, Windows 8-core $0.042/min). | **Free plan**: 1 Microsoft-hosted job with 1,800 minutes/month + 1 self-hosted job with unlimited minutes; public open-source projects receive 10 free parallel jobs. |
| **[GitHub Actions](https://github.com/features/actions)** | **~$100 Billion+** valuation (Microsoft subsidiary) / **$1B+** ARR | Native CI/CD embedded in GitHub with 20,000+ Marketplace actions. Self-hosted runner usage carries a $0.002/minute platform charge (drawn from free quota). | **Free plan**: 2,000 minutes/month for private repositories; **public repositories have 100% free unlimited minutes** (up to 20 concurrent jobs). |
| **[Bitbucket Pipelines](https://bitbucket.org/product/features/pipelines)** | **~$50 Billion** market cap (Atlassian) / **$4.4B+** annual revenue | Integrated CI/CD built directly into Atlassian Bitbucket with tight Jira and Confluence integrations. | Standard: **$3/user/month**; Premium: **$6/user/month** (annual billing). | **Free plan**: 5 users, 50 build minutes/month per workspace, and up to **100 free basic self-hosted runners** included. |
| **[GitLab CI/CD](https://about.gitlab.com/)** | **~$8.5 Billion** market cap (NASDAQ: GTLB) / **$750M+** ARR | Integrated DevSecOps platform with `.gitlab-ci.yml` pipelines, Auto DevOps, and native Kubernetes cluster integrations. | Premium: **$29/user/month** (annual commitment); Ultimate: **$99/user/month**. | **Free plan**: 400 compute minutes/month per namespace, up to 5 user seats, and **unlimited self-hosted runners** (0 minutes charged). |
| **[CircleCI](https://circleci.com/)** | **$1.7 Billion** valuation (Series F) / **~$60M** ARR | Cloud-native CI/CD featuring reusable Orbs, Docker layer caching, automated test splitting, and dynamic config generation. | Performance: **$15/month** base (includes 30,000 credits; additional credits at $15 per 25,000 credits). | **Free plan**: 30,000 build credits/month (~3,000 Linux build minutes), 5 active users, 5 self-hosted runners, and 1 macOS concurrent job (credits expire monthly). |
| **[Travis CI](https://www.travis-ci.com/)** | **~$1.1 Billion** parent valuation (Idera, Inc.) / **~$200M+** parent revenue | Pioneer cloud CI platform utilizing `.travis.yml` configs for multi-language testing matrix workflows. | Usage Based: **$13.75/month** (includes 420,000 Linux build credits/year and 80 concurrent jobs); Unlimited: **$66/month**. | **Free trial**: 10,000 one-time trial build credits (approx. 1,000 Linux build minutes) valid for up to **14 days** (or until credits exhaust). |
| **[TeamCity](https://www.jetbrains.com/teamcity/)** | **~$650 Million+** annual revenue / Bootstrapped multi-billion private tier (JetBrains) | JetBrains' continuous integration and build management engine with intelligent test execution and build history analysis. | Cloud: **$15/committer/month** (minimum 3 committers = $45/month, includes 24,000 build credits); On-premises Enterprise: **$2,399/year**. | **Professional (On-Premises)**: **Free forever** with 3 build agents, 100 build configurations, and unlimited users; **Cloud**: **14-day free trial** with full agent access. |
| **[Codefresh](https://codefresh.io/)** | **~$50 Million** acquisition price (acquired by Octopus Deploy) / **~$85M** combined ARR | Kubernetes-native CI/CD and GitOps platform natively integrated with Argo CD and enterprise cluster workflows. | Starter SaaS: **$99/month**; Enterprise GitOps contracts start around **$1,250/month** ($15,000/year). | **Free plan**: 1 concurrent build, up to 500 build minutes/month, and community GitOps integration; **14-day free trial** for enterprise tiers. |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[nektos/act](https://github.com/nektos/act)** | [![Stars](https://img.shields.io/github/stars/nektos/act?style=social&color=white)](https://github.com/nektos/act/stargazers) | Run GitHub Actions locally inside Docker containers. Enables rapid local testing and iterative development of CI workflows without pushing commits. |
| **[Jenkins](https://github.com/jenkinsci/jenkins)** | [![Stars](https://img.shields.io/github/stars/jenkinsci/jenkins?style=social&color=white)](https://github.com/jenkinsci/jenkins/stargazers) | The industry-standard open-source automation server (MIT). Features 1,800+ community plugins supporting every language, cloud provider, and build toolchain. |
| **[Argo CD](https://github.com/argoproj/argo-cd)** | [![Stars](https://img.shields.io/github/stars/argoproj/argo-cd?style=social&color=white)](https://github.com/argoproj/argo-cd/stargazers) | Declarative, GitOps continuous delivery tool for Kubernetes (CNCF graduated). Automatically synchronizes live application states with Git repository declarations. |
| **[Argo Workflows](https://github.com/argoproj/argo-workflows)** | [![Stars](https://img.shields.io/github/stars/argoproj/argo-workflows?style=social&color=white)](https://github.com/argoproj/argo-workflows/stargazers) | Container-native workflow engine orchestrating parallel jobs on Kubernetes (CNCF graduated). Define DAGs or sequential steps with artifact management and cron scheduling. |
| **[Spinnaker](https://github.com/spinnaker/spinnaker)** | [![Stars](https://img.shields.io/github/stars/spinnaker/spinnaker?style=social&color=white)](https://github.com/spinnaker/spinnaker/stargazers) | Multi-cloud continuous delivery platform originally developed by Netflix for enterprise automated releases across AWS, GCP, Azure, and Kubernetes with automated canary analysis. |
| **[Tekton Pipelines](https://github.com/tektoncd/pipeline)** | [![Stars](https://img.shields.io/github/stars/tektoncd/pipeline?style=social&color=white)](https://github.com/tektoncd/pipeline/stargazers) | Cloud-native, Kubernetes-standard CI/CD building blocks (CDF graduated). Provides CRDs for defining modular, portable, and reusable multi-stage pipeline workflows. |
| **[Flux CD](https://github.com/fluxcd/flux2)** | [![Stars](https://img.shields.io/github/stars/fluxcd/flux2?style=social&color=white)](https://github.com/fluxcd/flux2/stargazers) | Set of continuous and progressive delivery controllers for Kubernetes (CNCF graduated). Powers open and extensible GitOps pipelines. |
| **[Woodpecker CI](https://github.com/woodpecker-ci/woodpecker)** | [![Stars](https://img.shields.io/github/stars/woodpecker-ci/woodpecker?style=social&color=white)](https://github.com/woodpecker-ci/woodpecker/stargazers) | Lightweight, community-driven, container-based continuous integration engine (fork of Drone 0.8) running pipelines in isolated containers with simple YAML specs. |
| **[Concourse CI](https://github.com/concourse/concourse)** | [![Stars](https://img.shields.io/github/stars/concourse/concourse?style=social&color=white)](https://github.com/concourse/concourse/stargazers) | Open-source continuous thing-doer built on simple mechanics: tasks, resources, and jobs. Purely declarative, stateless, and containerized pipeline automation. |
| **[Danger](https://github.com/danger/danger)** | [![Stars](https://img.shields.io/github/stars/danger/danger?style=social&color=white)](https://github.com/danger/danger/stargazers) | Connects with CI systems and pull request review workflows to automate PR checks, enforce team norms, and post lint/security findings directly in code review threads. |
| **[CDS](https://github.com/ovh/cds)** | [![Stars](https://img.shields.io/github/stars/ovh/cds?style=social&color=white)](https://github.com/ovh/cds/stargazers) | Enterprise-grade continuous delivery and DevOps automation platform written in Go by OVHcloud. Features complex pipeline DAGs, built-in artifact storage, and self-hosted worker clustering. |
| **[PHP Censor](https://github.com/php-censor/php-censor)** | [![Stars](https://img.shields.io/github/stars/php-censor/php-censor?style=social&color=white)](https://github.com/php-censor/php-censor/stargazers) | Open-source self-hosted continuous integration server specifically tailored for PHP development teams and automated test suites. |

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- CI/CD platforms handle source code, credentials, and deployment access; enforce least-privilege runner permissions, mask secrets in logs, and isolate self-hosted runners.
- Pricing changes frequently: GitHub Actions introduced a self-hosted platform charge in March 2026, Bitbucket added a 100-runner free tier, and Azure Pipelines offers pay-as-you-go GitHub-hosted agents. Always verify against vendor pricing pages before committing.

---

**Made for DevOps engineers, platform teams, and developers building automated delivery pipelines.**  
Let's make CI/CD integrations more open, automatable, and cost-predictable.
