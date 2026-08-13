# DevOps Engineer — Zero-Budget, Job-Ready Roadmap (2026 Edition)

> Target: employed within 5–6 months. Commitment: 4–6 focused hours daily. Budget: $0.
> Grounded in live 2026 market data: analysis of 7,500+ active DevOps job postings, DORA/CNCF survey trends, and skills-based hiring reports (TestGorilla 2025: 53% of employers removed degree requirements from some postings).

---

# Part 1 — Career Overview

## What this career actually does

DevOps engineers build and operate the "delivery factory" of software companies. You are the person who makes sure that when a developer commits code, it is automatically tested, built, containerized, deployed safely to production, monitored, and — when something breaks — rolled back or fixed faster than anyone else can.

Practically, DevOps in 2026 means owning:

- **CI/CD pipelines** — automated build, test, and deploy (GitHub Actions, GitLab CI, Jenkins)
- **Infrastructure as Code (IaC)** — servers, networks, and clusters defined in version-controlled code (Terraform)
- **Containers & orchestration** — packaging apps with Docker and running them at scale with Kubernetes
- **Cloud platforms** — AWS (most common), Azure, or GCP
- **Observability** — monitoring, logging, tracing (Prometheus, Grafana, OpenTelemetry)
- **Reliability** — uptime, incident response, rollbacks, autoscaling, disaster recovery
- **Developer productivity** — internal platforms and self-service tooling

## Daily responsibilities

- Reviewing and improving pipeline configs (YAML, mostly)
- Debugging failed deployments and production incidents
- Writing Terraform to provision infrastructure
- Dockerizing apps, optimizing container images, scanning them for vulnerabilities
- Managing Kubernetes clusters: scaling, upgrades, security, troubleshooting
- Setting up alerts and dashboards; responding to pages during on-call rotation
- Automating anything done manually more than twice
- Documenting runbooks and teaching developers how to use the infrastructure
- About 30–50% of the job is communication: writing things down, explaining outages, unblocking other engineers

## Who hires for this role

- **Enterprises** (banks, insurance, telecom, retail, healthcare) modernizing legacy infrastructure — the biggest single hiring block in 2026
- **Consulting/services firms** (Accenture, PwC, Booz Allen) that deploy DevOps teams client-side
- **Defense & government contractors** (security-clearance roles, lower competition)
- **Product companies** (SaaS, fintech, AI startups) — often under titles like Platform Engineer, SRE, or Infrastructure Engineer
- **DevOps agencies** (build pipelines and infrastructure for other companies)
- **AI infrastructure teams** — GPU clusters, MLOps, serving infrastructure (fastest-growing slice, 15–25% salary premium)

## Current demand

- Interview activity for DevOps roles grew **54% in 7 months** (Sept 2025 → April 2026) in an analysis of 816,000+ interview sessions.
- Table-stakes skills appear in more than half of all postings: **CI/CD (67%), automation (58%), Kubernetes (56%), AWS (54%), Python (53%), Terraform (~50%)**.
- Global DevOps market projected to grow ~20% CAGR to $81B by 2033.
- **Caveat:** only ~2% of DevOps postings are explicitly "entry-level." Entry happens through internships, adjacent roles (cloud support, backend+DevOps hybrids, support engineering), and portfolios so strong they override the "years of experience" filter.

## Remote opportunities

- ~40% of DevOps postings in mid-2026 are fully remote; hybrid is the most common default at enterprises.
- DevOps is one of the most remote-friendly careers — infrastructure is managed over SSH/APIs, and on-call is distributed by design.
- Global remote competition is real: to win a remote junior role you must show deployed, running, observable systems in your portfolio — not certificates.

## Freelancing opportunities

Excellent, and unusually good for a junior because the work is bounded and demonstrable:

- "Set up CI/CD for my team" (3–7 days of work)
- "Containerize our legacy app" (2–5 days)
- "Build Terraform for our AWS account" (1–2 weeks)
- "Fix our broken Kubernetes cluster" (urgent, high-paying)
- "Set up monitoring dashboards and alerts" (days)
- Rates: $25–$60/hr entry freelance; $80–$150/hr with a track record. Platforms: Upwork, Contra, Fiverr (see Part 14).

## Salary ranges (2026, base salaries)

| Market | Entry (0–2 yr) | Mid (3–5 yr) | Senior (6+ yr) |
|---|---|---|---|
| US (median base) | $80K–$110K | $110K–$140K (median ~$129K) | $140K–$200K+ |
| EU (Western) | EUR 45–65K | EUR 65–90K | EUR 90–130K |
| India | INR 5–12 LPA | INR 12–22 LPA | INR 22–40 LPA |
| Remote global (freelance) | $25–$50/hr | $50–$90/hr | $90–$150/hr |

Reliability-tier skills (SLOs, OpenTelemetry, incident response, observability) correlate with medians of **$145K–$160K US** — a $20–30K premium over baseline. Specializations (Platform Engineer, SRE, DevSecOps, MLOps) pay 15–25% above generalist DevOps.

## Future growth

Strong for at least the next decade. Drivers: continued cloud migration (a large share of enterprise workloads still run on-prem), platform engineering becoming the standard entry point, security integration (DevSecOps is a compliance requirement in finance/healthcare/government), and AI infrastructure needing operators (GPU fleets, model serving, ML pipelines). The role is consolidating: fewer "click-the-console" ops jobs, more code-driven infrastructure work.

## Difficulty level

**Hard to start, easier to master.** The learning curve is steeper than web development because you touch many layers (OS, networks, containers, cloud, code). But the barrier is breadth, not depth: a disciplined 6-month plan with daily practice gets you employable. The hard part is avoiding "tutorial hell" — this field punishes passive watching.

## Who this career is best suited for

- People who like debugging and root-cause analysis (detective work)
- Tinkerers who enjoy running their own servers, self-hosting, modding systems
- Methodical note-takers — documentation is half the job
- People who stay calm under pressure (on-call and incidents)
- Those who prefer broad systems knowledge over deep single-topic mastery
- People who can tolerate command lines, YAML, and dry documentation

## Mistakes beginners make

1. **Skipping Linux/Git fundamentals** and jumping straight to Kubernetes tutorials — everything becomes magic you can't debug
2. **Clicking through cloud consoles** instead of writing code (Terraform, CLI) — you learn the UI, not the trade
3. **Tool-hopping** — chasing every new tool the internet mentions and finishing none
4. **Never deploying anything** — months of courses without one running system
5. **Ignoring security** — insecure pipelines are an instant interview fail
6. **No documentation habit** — runbooks and READMEs are what juniors get hired for
7. **Learning instead of building** — the "I'll start projects once I finish the course" trap
8. **Copy-pasting configs** without understanding them (then failing any follow-up question)
9. **Not accounting for cloud costs** — or being afraid of the free tier (use it aggressively)
10. **Applying before having deployable proof** — with 2% entry-level postings, the portfolio IS your entry ticket

## Current industry trends

- **Platform engineering** is the fastest-growing specialization — internal developer platforms (IDPs) that wrap AWS/K8s in self-service interfaces
- **GitOps** (ArgoCD/Flux) is now the default way teams manage Kubernetes state
- **Observability is converging on OpenTelemetry** — one unified standard for traces, metrics, logs
- **AI is ambient**: 85–90% of engineers use AI assistants daily (JetBrains/DORA surveys) for Terraform authoring, kubectl debugging, runbook drafting
- **DevSecOps is mandatory**, not optional — security scanning inside CI is normal
- **FinOps** — cost optimization is a named responsibility now
- **Skills-based hiring**: 53% of employers dropped degree requirements; portfolios beat certifications

## AI's impact on this career

Three layers, all good news for you:

1. **Ambient AI (everyone):** AI assistants write boilerplate Terraform/YAML, explain errors, suggest kubectl commands. This lowers the barrier to entry — but interviewers quickly detect candidates who can't explain what the AI produced. AI makes you faster; understanding makes you employable.
2. **AI in the stack:** predictive alerting, log anomaly detection, auto-remediation bots. Growing line on job descriptions.
3. **AI infrastructure work:** ~12% of DevOps postings now hire specifically for AI/ML infrastructure; rising fast with salary premiums.

**Net impact:** the generalist plateau is shrinking. The reliability tier (SLOs, observability, incident discipline, security) is where humans remain irreplaceable — 2026 data shows that's exactly where the $160K medians live. Plan your roadmap accordingly (see Weeks 22–23).

## How this role will evolve over the next five years

- **2026–2027 (your entry window):** DevOps Engineer is a broad role — CI/CD + containers + cloud + IaC. Juniors get in through internships, platform engineering, and support-adjacent roles.
- **2027–2029 (mid):** Consolidation into Platform Engineer / SRE with strong observability and security ownership. Multi-cloud and cost-engineering become expected.
- **2029–2031 (senior):** "Compute is a commodity, operations is a product." Senior roles: platform product managers of infrastructure, reliability engineers owning SLOs, AI-infra specialists running GPU fleets and model serving pipelines. eBPF, WebAssembly, and edge computing enter the mainstream toolkit.
- The meta-skills that survive every tool change: **Linux fundamentals, networking, IaC thinking, incident discipline, systems troubleshooting, clear documentation.**

---

# Part 2 — Skills Breakdown

Legend: MUST = Must Know (appears on most JDs) | G2K = Good to Know (differentiator) | OPT = Optional | FUT = Future

## MUST 1. Linux & the CLI

- **Why it matters:** 90%+ of servers, containers, and prod environments run Linux. Every job description assumes it (31% name it explicitly; implied in the rest).
- **Where used:** daily — filesystem, processes, logs, permissions, SSH, systemd, network tools
- **Companies that expect it:** every company with servers — read it as 100%
- **Learning time:** 40–60 hours to operational; a lifetime to mastery
- **Difficulty:** low-medium (memorization + repetition)
- **Prerequisites:** none — this is your first skill
- **Checklist:** file ops, chmod/chown/umask, pipes and redirection, grep/sed/awk basics, processes (ps, top, kill), systemd services, SSH + keys, networking (ip, ss, curl, nc, dig), cron, disk and memory management, journalctl/logs

## MUST 2. Git & GitHub

- **Why it matters:** Git is the version-control system for code, infrastructure, and pipelines. GitOps ("everything in Git") is the industry default. GitHub is also your portfolio and increasingly your CI system.
- **Where used:** every commit, every PR, every pipeline trigger, every Terraform change
- **Companies that expect it:** 100% — expected on day 0
- **Learning time:** 25–40 hours to fluency
- **Difficulty:** low
- **Prerequisites:** none
- **Checklist:** init/clone/status/log, add/commit/push/pull, branches, merges, rebase, conflicts, remote management, PR flow, issues, tags, releases, branching strategies (GitHub Flow, trunk-based)

## MUST 3. Bash scripting

- **Why it matters:** "automation" appears in 58% of JDs. Every server task — backups, log rotation, health checks, deployments — is scripted.
- **Where used:** cron jobs, pipeline steps, server bootstrap, glue between tools
- **Companies that expect it:** essentially all (often listed as "shell scripting")
- **Learning time:** 30–50 hours
- **Difficulty:** medium
- **Prerequisites:** Linux basics
- **Checklist:** variables, conditionals, loops, functions, $@/$?/exit codes, command substitution, string handling, error handling (set -euo pipefail, traps), sed/awk/jq, ShellCheck-verified scripts

## MUST 4. Python

- **Why it matters:** the #1 automation language; 53% of postings. Used for tooling, AWS boto3, pipeline logic, log/API processing. Also your interview language.
- **Where used:** custom tooling, automation scripts, CI logic, data processing
- **Companies that expect it:** most (Go is the newer alternative)
- **Learning time:** 40–60 hours for practical automation level
- **Difficulty:** low-medium
- **Prerequisites:** Linux basics help
- **Checklist:** syntax, data structures, file I/O, functions, modules, error handling, HTTP requests, JSON/YAML handling, pytest basics, virtual environments

## MUST 5. Docker & Containers

- **Why it matters:** containers are the default packaging unit of modern software (38% of JDs name Docker; implied far beyond — K8s is meaningless without it).
- **Where used:** every app you deploy, every image you build, every local dev environment
- **Companies that expect it:** all cloud-native companies + enterprises modernizing
- **Learning time:** 40–60 hours
- **Difficulty:** medium
- **Prerequisites:** Linux (namespaces/cgroups concepts), Git
- **Checklist:** images vs containers, Dockerfiles (multi-stage, layer caching, non-root users), volumes & bind mounts, networks, docker-compose, registries (GHCR/Docker Hub), image size optimization, .dockerignore, basic image security (trivy)

## MUST 6. CI/CD

- **Why it matters:** THE #1 skill on job descriptions — 67% name it; it is the core of the job.
- **Where used:** every code change flows through a pipeline. GitHub Actions is the most beginner-friendly and startup-standard; GitLab CI is enterprise-favorite; Jenkins still exists in legacy orgs.
- **Companies that expect it:** 100%
- **Learning time:** 50–80 hours across Actions + GitLab CI
- **Difficulty:** medium
- **Prerequisites:** Git, Bash, Docker, some Python
- **Checklist:** triggers/events, jobs/steps/stages, caching, artifacts, env vars & secrets, matrix builds, gates/approvals, Docker build & push, deploy jobs, pipeline security hardening, tests-before-merge workflows

## MUST 7. AWS (one cloud, deeply)

- **Why it matters:** AWS appears in 54% of postings — the dominant cloud. Depth in one cloud beats shallow knowledge of three.
- **Where used:** everything you deploy, provision, and operate
- **Companies that expect it:** AWS shops (majority); Azure in banks/enterprise; GCP in startups/ML
- **Learning time:** 80–120 hours hands-on (free tier)
- **Difficulty:** medium-high (breadth)
- **Prerequisites:** Linux, networking concepts
- **Checklist:** IAM (users, roles, policies, least privilege), VPC (subnets, routing, security groups, NACLs), EC2 (instances, AMIs, key pairs, user-data), S3 (buckets, lifecycle, versioning, presigned URLs), RDS/DynamoDB, Lambda, CloudWatch (logs, alarms, metrics), Route 53, ALB/ELB, autoscaling, SQS/SNS basics, cost management (billing alerts, free-tier boundaries)

## MUST 8. Terraform (IaC)

- **Why it matters:** infrastructure-as-code on ~50% of JDs; pairs with AWS (37% co-occurrence), K8s (39%), CI/CD (42%). The #1 IaC tool in 2026.
- **Where used:** provisioning everything — VPCs, EC2, clusters, S3, DNS, users
- **Companies that expect it:** the overwhelming majority
- **Learning time:** 60–100 hours
- **Difficulty:** medium-high (state management trips everyone)
- **Prerequisites:** AWS basics, Git, moderate Bash
- **Checklist:** providers, resources, data sources, variables & locals, outputs, state (concepts, locking, remote state in S3), modules, plan/apply workflow, workspaces, import, drift, sensitive values, terraform fmt/validate, checkov policy checks

## MUST 9. Kubernetes

- **Why it matters:** de facto orchestrator — 56% of JDs and the tool most likely to appear in the job title. Moving on-prem infra to K8s is a permanent industry project.
- **Where used:** running production workloads at scale; GitOps; microservices
- **Companies that expect it:** most mid/large orgs, all cloud-native shops
- **Learning time:** 100–150 hours to interview-fluent (the biggest single skill)
- **Difficulty:** high (concepts + YAML + debugging)
- **Prerequisites:** Docker, networking, YAML comfort
- **Checklist:** architecture (control plane vs nodes, etcd, kubelet, scheduler), pods, deployments, replicasets, services, ingress, configmaps/secrets, namespaces, probes (liveness/readiness), storage (PV/PVC), labels/selectors, Helm basics, kubectl fluency, kind/minikube cluster ops, RBAC basics, HPA scaling, troubleshooting (describe, logs, port-forward, exec)

## MUST 10. Observability: Prometheus + Grafana (+ OpenTelemetry basics)

- **Why it matters:** the reliability tier pays $20–30K above baseline. Monitoring appears in 47% of postings; observability in 32% and rising.
- **Where used:** every production system, every incident, every capacity decision
- **Companies that expect it:** all (Datadog in enterprises; the free stack is Prometheus+Grafana)
- **Learning time:** 40–60 hours
- **Difficulty:** medium
- **Prerequisites:** Linux, Docker, basic networking
- **Checklist:** metrics vs logs vs traces, PromQL basics, exporters, alerting rules + Alertmanager, Grafana dashboards, log aggregation (Loki basics), OpenTelemetry concepts, SLO/SLI and error budgets

## G2K 11. Ansible (config management)

- **Why it matters:** ~25% of JDs; the standard for configuring servers where Terraform stops. Terraform = provision, Ansible = configure.
- **Learning time:** 30–50 hours | **Difficulty:** medium | **Prereqs:** Linux, YAML
- **Checklist:** inventory, playbooks, modules, handlers, variables, templates, idempotency, ad-hoc commands

## G2K 12. Helm + GitOps (ArgoCD or Flux)

- **Why it matters:** K8s in production is packaged with Helm and deployed with GitOps. ArgoCD correlates with ~$140K medians.
- **Learning time:** 30–50 hours | **Difficulty:** medium-high | **Prereqs:** Kubernetes
- **Checklist:** Helm charts (create, install, upgrade, values), templating; ArgoCD apps, sync policies, self-healing, desired vs observed state

## G2K 13. GitLab CI

- **Why it matters:** enterprise standard; single-file .gitlab-ci.yml skills transfer everywhere.
- **Learning time:** 20–30 hours after Actions | **Difficulty:** medium | **Prereqs:** CI/CD concepts

## G2K 14. Networking fundamentals

- **Why it matters:** every deployment decision is a networking decision; interviewers probe this hard.
- **Learning time:** 30–40 hours | **Difficulty:** medium | **Prereqs:** none
- **Checklist:** OSI model, TCP/UDP, DNS, HTTP/HTTPS, TLS, IP addressing/subnetting, NAT, load balancing, firewalls, proxies, common failure modes (DNS, certs, ports)

## G2K 15. Security / DevSecOps fundamentals

- **Why it matters:** security-integrated delivery is a durable, compliance-driven hiring wave (DevSecOps roles: $140–190K).
- **Learning time:** 30–40 hours woven into other topics | **Difficulty:** medium | **Prereqs:** CI/CD, Linux
- **Checklist:** secret management, least privilege, image scanning (trivy), dependency/SAST scanning in pipelines, OWASP Top 10 awareness, TLS everywhere, SIGTERM handling, RBAC basics, policy-as-code (checkov/OPA awareness)

## G2K 16. Cloud CLI + cost awareness (FinOps basics)

- **Learning time:** 15–25 hours | **Difficulty:** low | **Prereqs:** chosen cloud
- **Checklist:** aws cli fluency, cost explorer, budget alarms, right-sizing instinct

## OPT 17. Jenkins (legacy CI)

Exists in the wild: banks, old enterprises, government. Learn concepts; don't invest deeply. 15–20 hours max.

## OPT 18. Go

The language Kubernetes/Terraform/Argo are written in. High signal for platform roles; useful for operators/CLIs. 40–60 hours — only after Python and everything above.

## OPT 19. Service mesh (Istio/Linkerd)

Growing but not table stakes. ~20 hours of concepts + a demo after K8s is deep.

## OPT 20. Azure / GCP (second cloud)

After AWS depth, one week of mapping gets you interview-ready for "other cloud" questions.

## OPT 21. Web tech basics (HTML/CSS/JS)

Only needed for the portfolio site. 20 hours max.

## OPT 22. SQL basics

Helps with log querying and data-heavy pipelines. 15 hours.

## FUT 23. Platform Engineering (IDPs)

Building developer self-service layers over cloud/K8s. The fastest-growing specialization and the most realistic junior entry door. Follow: CNCF platforms whitepaper, Backstage docs (open source).

## FUT 24. eBPF (Cilium, Falco, bpftrace)

Kernel-level visibility and security; increasingly expected in K8s networking/security roles. Start after K8s.

## FUT 25. MLOps / AI infrastructure

GPU cluster ops, model serving (vLLM, KServe), ML pipelines (Kubeflow). Premium roles; learn the entry concepts in Year 1–2.

## FUT 26. WebAssembly / edge computing

The next runtime frontier after containers.

## FUT 27. Financial engineering (FinOps)

Cost-as-code: budgets, tagging, rightsizing automation. Already a named responsibility on JDs.

---

# Part 3 — 5 to 6 Month Weekly Roadmap

Daily time budget (4–6 hours):
- **2h** — structured learning (videos/docs, hands-on alongside)
- **2.5h** — build/practice (projects, labs, scripts)
- **1h** — notes, revision, daily Git commits
- **0.5h** — LeetCode / Exercism / OverTheWire muscle training

> Golden rule: **type everything you learn.** No video counts unless you typed the commands yourself.

## Phase A — Foundations (Weeks 1–5)

### Week 1 — Linux Essentials, Part 1

- **Objectives:** comfortable CLI operator; filesystem mental model
- **Topics:** what Linux is (kernel, distros), filesystem hierarchy, navigation (cd, ls, pwd), file ops (cp, mv, rm, touch, mkdir, ln), file inspection (cat, less, head, tail, file), man pages, text editors (vim survival mode: i, esc, :wq), grep, pipes & redirection, users and permissions (chmod, chown, umask), help (--help, man)
- **Practice:** install Ubuntu in WSL2 (Windows) or dual boot; 30-min terminal drills daily; maintain a Markdown cheat sheet you update every day
- **Mini project:** "Daily Log": a directory tree plus a cron-scheduled script that timestamps a log file — read it back with tail -f
- **Reading:** Linux Journey (linuxjourney.com) — Paths, File systems, Permissions
- **Videos:** freeCodeCamp "The Linux Command Line" or Learn Linux TV "Linux Essentials" playlist (pick the newest on YouTube)
- **Documentation:** man pages; nothing fancier yet
- **Assignments:** OverTheWire Bandit levels 0–5 (overthewire.org/wargames/bandit)
- **Revision:** 20-min quiz on commands; retype yesterday's drills from memory
- **Checkpoint:** in under 60 seconds: navigate to a nested dir, create 3 files, chmod one executable, grep for a pattern
- **Time estimate:** 28–35 hours
- **Expected outcome:** you think in paths; the terminal no longer scares you

**Daily suggestions:** Mon: setup + first 20 commands. Tue: navigation drills + cheat sheet. Wed: file ops + permissions. Thu: grep/pipes + Bandit 0–3. Fri: vim + man pages. Sat: build the Daily Log project. Sun: revision quiz + update cheat sheet.

### Week 2 — Linux Essentials, Part 2

- **Objectives:** manage processes, services, users, disk, and networking from the CLI
- **Topics:** processes (ps, top, htop, kill, kill -9 vs -15), systemd (systemctl, journalctl), cron & systemd timers, user management (useradd, usermod, groups, su/sudo), disk (df, du, free), networking (ip, ss, curl, ping, dig, nc), SSH (keys, config, scp/rsync), env vars and PATH, tar/zip, awk/sed basics, shell history and aliases
- **Practice:** SSH into a free Oracle Cloud Always Free Ubuntu VM; harden it (new user, key-only auth, no root login)
- **Mini project:** "Server Shop": run a static web server, schedule a restart with systemd timer, harden SSH
- **Reading:** The Linux Command Line (free PDF, linuxcommand.org/tlcl.php) ch. 1–10
- **Videos:** Learn Linux TV "Linux Crash Course" episodes on SSH, systemd, permissions
- **Assignments:** Bandit levels 6–15
- **Revision:** rebuild last week's cheat sheet from memory, then diff it against the original
- **Checkpoint:** create a user, add SSH key, lock root login, verify with a fresh ssh session — all without searching
- **Time estimate:** 30–35 hours
- **Expected outcome:** you can operate a remote Linux server responsibly

**Daily suggestions:** Mon: processes + systemd. Tue: users + sudo. Wed: SSH end-to-end. Thu: networking tools. Fri: cron/timers + awk/sed. Sat: Server Shop project + VM hardening. Sun: full review + Bandit catch-up.

### Week 3 — Git & GitHub Mastery

- **Objectives:** Git fluency; clean PR workflow; GitHub as portfolio + CI surface
- **Topics:** init/clone/status/log/diff, add/commit/push/pull, branches, merges vs rebase, conflict resolution, .gitignore, remotes, tags, GitHub Flow, PRs and reviews, issues, GitHub Pages basics, GitHub CLI (gh)
- **Practice:** create repos daily; force yourself to use branches even for tiny changes; write a script and PR it to yourself
- **Mini project:** "My Dev Journal" repo — daily commit of notes with proper messages; turn it into a GitHub Pages site
- **Reading:** Pro Git (git-scm.com/book/en/v2) ch. 1–6
- **Videos:** freeCodeCamp "Git and GitHub for Beginners — Crash Course" (2025/2026 edition on freeCodeCamp YouTube)
- **Interactive:** Learn Git Branching (learngitbranching.js.org) — finish every level
- **Assignments:** GitHub Skills (skills.github.com) — Introduction to GitHub + Communicate using Markdown + Reviewing pull requests
- **Revision:** explain merge vs rebase to yourself in writing (you will get asked this in interviews)
- **Checkpoint:** resolve a synthetic merge conflict in under 5 minutes
- **Time estimate:** 25–30 hours
- **Expected outcome:** Git operations are muscle memory; your profile shows a commit streak starting now

**Daily suggestions:** Mon–Tue: core Git (learn git branching levels). Wed: remotes + GitHub. Thu: merge vs rebase practice. Fri: GitHub Skills courses. Sat: journal-to-Pages site + first proper PR. Sun: review + write the merge-vs-rebase explainer.

### Week 4 — Bash Scripting

- **Objectives:** write reliable automation scripts that are safe to run on a server
- **Topics:** shebangs, variables, conditionals, loops, functions, exit codes, command substitution, string manipulation, arrays, error handling (set -euo pipefail, traps), jq for JSON, sed/awk deeper, ShellCheck
- **Practice:** rewrite every manual command sequence from Weeks 1–2 as a script; lint with ShellCheck
- **Mini project:** "Backup & Rotate": a script that tars a directory, timestamps backups, keeps the last 7, and reports via curl to a webhook
- **Reading:** Bash Guide (mywiki.wooledge.org/BashGuide) sections: Scripting, Error handling
- **Videos:** freeCodeCamp "Bash Scripting" full course or Learn Linux TV "Bash scripting" playlist
- **Assignments:** HackerRank Linux Shell track (20 problems) — this trains the exact muscle interviewers test
- **Revision:** refactor an old script to be idempotent (safe to run twice)
- **Checkpoint:** write, from a blank file, a backup script with set -euo pipefail that survives a bug you deliberately insert
- **Time estimate:** 30–35 hours
- **Expected outcome:** you can automate real server tasks without fear

**Daily suggestions:** Mon: syntax + variables. Tue: conditionals/loops. Wed: functions + exit codes. Thu: error handling + traps. Fri: jq/sed/awk. Sat: Backup & Rotate project + ShellCheck pass. Sun: HackerRank shell problems + review.

### Week 5 — Python for Automation

- **Objectives:** Python as your automation and interview language
- **Topics:** syntax, data structures, file I/O, functions, modules, error handling, virtual environments (venv), pip, HTTP requests (requests/urllib), JSON/YAML handling, argparse, pytest basics, boto3 preview
- **Practice:** re-implement the Week 4 backup script in Python with tests
- **Mini project:** "System Report": Python script that gathers disk/memory/network info from a remote server over SSH and emails or posts a summary to a Slack webhook
- **Reading:** Automate the Boring Stuff with Python (free online, automatetheboringstuff.com) — ch. 1–14 selectively
- **Videos:** freeCodeCamp "Learn Python — Full Course for Beginners" (4h, pick newest) or TechWorld with Nana "Python for DevOps" if available
- **Interactive:** Exercism Python track (exercism.org) — 20 exercises
- **Assignments:** LeetCode easy problems #1, #217, #125, #20, #121 in Python
- **Revision:** compare Bash vs Python solutions for the same task; note when each is right
- **Checkpoint:** write a tested Python script that reads a YAML config, does something, and exits 0/1 properly
- **Time estimate:** 35–40 hours
- **Expected outcome:** you can script real automation and solve interview problems in Python

**Daily suggestions:** Mon: syntax + structures. Tue: files + functions. Wed: requests + JSON. Thu: pytest + venv. Fri: argparse + boto3 preview. Sat: System Report project. Sun: LeetCode + Exercism batch + revision.

---

## Phase B — Containers (Weeks 6–8)

### Week 6 — Docker Fundamentals

- **Objectives:** build, run, and inspect containers confidently; understand the container mental model
- **Topics:** containers vs VMs, images vs containers, Dockerfile basics, docker run/build/exec/logs/ps/rm, ports and volumes, docker inspect, layers and caching, .dockerignore, entrypoint vs CMD, non-root users, multi-stage builds
- **Practice:** containerize a small app (any simple Flask or Node app); iteratively shrink image size
- **Mini project:** "Day-0 Image": production-grade Dockerfile for a small Flask app — non-root, multi-stage, slim image under 150MB, HEALTHCHECK
- **Reading:** Docker curriculum (github.com/prakhar1989/docker-curriculum) — Build your first image onward
- **Videos:** TechWorld with Nana "Docker Tutorial for Beginners [FULL COURSE in 3 Hours]" (YouTube, still the gold standard)
- **Interactive:** Play with Docker (labs.play-with-docker.com) — browser-based practice
- **Assignments:** Docker official getting-started tutorial (docs.docker.com/get-started)
- **Revision:** explain container networking (bridge, host, none) from memory in writing
- **Checkpoint:** build a containerized app, run it, exec into it, modify a file, verify isolation
- **Time estimate:** 35–40 hours
- **Expected outcome:** you can package any simple application reproducibly

**Daily suggestions:** Mon: concepts + first run. Tue: Dockerfile + build. Wed: volumes + ports. Thu: multi-stage + optimization. Fri: networking + inspect. Sat: Day-0 Image project + trivy scan. Sun: full revision + write the "containers vs VMs" essay.

### Week 7 — Docker Compose & Multi-Container Apps

- **Objectives:** orchestrate multi-service applications locally; service-to-service communication
- **Topics:** docker-compose.yml, services/networks/volumes, depends_on, environment variables, ports, health checks, profiles, compose secrets, dev vs prod overrides
- **Practice:** run the docker example-voting-app (GitHub: docker/example-voting-app) with compose and understand each service
- **Mini project:** "Full Local Stack": compose file running app + PostgreSQL + Redis + adminer with volumes and health checks — the stack you will reuse in every future project
- **Reading:** Docker Compose docs (docs.docker.com/compose) — full tutorial
- **Videos:** TechWorld with Nana "Docker Compose" tutorial, or Collabnix dockerlabs compose module
- **Assignments:** containerize and compose a second app of your own choice (e.g., a static site + nginx + certbot)
- **Revision:** diagram the network topology of your compose stack from memory
- **Checkpoint:** `docker compose up` a 4-service stack, persist data across restart, and tear down cleanly
- **Time estimate:** 30–35 hours
- **Expected outcome:** you can stand up realistic multi-tier environments locally — the core skill for CI and prod

**Daily suggestions:** Mon: compose syntax. Tue: networks + volumes in compose. Wed: voting-app study. Thu: health checks + profiles. Fri: build your own stack. Sat: polish + docs + diagram. Sun: revision + HackerRank shell catch-up.

### Week 8 — Container Registries, CI hooks, and Container Security

- **Objectives:** ship images to registries; scan for vulnerabilities; container security basics
- **Topics:** GitHub Container Registry (GHCR), tagging strategies (semver + sha), image signing awareness, trivy vulnerability scanning, .dockerignore hygiene, secrets in builds (BuildKit secrets, no ARG secrets), resource limits, read-only root filesystems, 12-factor awareness
- **Practice:** push every image you build to GHCR; add trivy scan to a local script
- **Mini project:** "Secure Image Pipeline": a local (soon CI) flow that builds → scans → pushes only if clean
- **Reading:** trivy docs (aquasecurity.github.io/trivy); Docker security best practices docs
- **Videos:** Docker docs video track or TechWorld Nana container security episode if present
- **Assignments:** write a "Docker Security Checklist" doc for your repo
- **Revision:** 15-minute quiz on Dockerfile best practices (multi-stage, non-root, healthcheck)
- **Checkpoint:** scan a deliberately vulnerable image, explain findings, fix the Dockerfile
- **Time estimate:** 25–30 hours
- **Expected outcome:** you ship images the way companies require — clean, scanned, tagged

**Daily suggestions:** Mon: GHCR + tagging. Tue: trivy. Wed: buildkit secrets. Thu: resource limits + read-only. Fri: 12-factor review. Sat: Secure Image Pipeline project. Sun: revision + LeetCode batch.

---

## Phase C — CI/CD (Weeks 9–10)

### Week 9 — CI/CD Concepts + GitHub Actions

- **Objectives:** build production-shaped pipelines: test → build → scan → push → deploy
- **Topics:** CI vs CD, pipelines, stages, jobs, triggers, actions ecosystem, runners (hosted vs self-hosted), secrets and environments, caching, artifacts, matrix builds, OIDC for cloud auth (no stored keys), approvals/gates
- **Practice:** add CI to ALL your existing repos (shellcheck, pytest, hadolint, trivy)
- **Mini project:** "Uni-Pipeline": one workflow that lints → tests → builds image → scans → pushes to GHCR; second workflow deploys the Flask app to a free Oracle Cloud VM via SSH
- **Reading:** GitHub Actions docs (docs.github.com/actions) — Learning GitHub Actions guide; starter-workflows repo (github.com/actions/starter-workflows)
- **Videos:** freeCodeCamp "GitHub Actions — Full Course" or TechWorld Nana "GitHub Actions Tutorial"
- **Assignments:** convert your Week 8 secure-image flow into a real workflow
- **Revision:** write a one-page explanation: "how a deploy happens from commit to production in my project"
- **Checkpoint:** commit a broken test → see CI fail → fix → green — 15 minutes, end to end
- **Time estimate:** 35–40 hours
- **Expected outcome:** the #1 hiring skill is demonstrably yours — with live green pipelines in your profile

**Daily suggestions:** Mon: concepts + first workflow. Tue: triggers + jobs. Wed: secrets + environments. Thu: matrix + caching. Fri: OIDC + AWS/SSH deploy. Sat: Uni-Pipeline project. Sun: write the end-to-end explainer + revision.

### Week 10 — GitLab CI + Deploy Strategies + Jenkins Concepts

- **Objectives:** second pipeline tool for enterprise JDs; deployment strategies that interviewers ask about
- **Topics:** GitLab CI: .gitlab-ci.yml, stages, rules, artifacts, environments, DAG; deployment strategies: blue/green, canary, rolling, recreate; rollbacks; Jenkins: what it is, where it lives, why legacy — concepts only
- **Practice:** mirror your Uni-Pipeline in a GitLab project (free tier, gitlab.com)
- **Mini project:** "Canary Demo": a deploy script that rolls out to 10% of traffic, checks a health endpoint, then 100% (use nginx upstreams or a simple weighted proxy)
- **Reading:** GitLab CI docs (docs.gitlab.com/ee/ci); search "deployment strategies" on the DevOps Encyclopedia repo
- **Videos:** TechWorld with Nana "GitLab CI CD Tutorial" (if current) or GitLab's own tutorials on YouTube
- **Assignments:** document blue/green vs canary vs rolling with pros/cons in your notes
- **Revision:** diagram your Uni-Pipeline as GitLab CI stages
- **Checkpoint:** explain to an imaginary interviewer: "Why not restart servers manually?" — 3 minutes, from memory
- **Time estimate:** 25–30 hours
- **Expected outcome:** pipeline skills transfer to any CI tool; you can speak deployment strategies fluently

**Daily suggestions:** Mon: GitLab CI basics. Tue: stages + rules. Wed: environments + artifacts. Thu: deploy strategies theory. Fri: canary demo build. Sat: GitLab mirror of pipeline. Sun: revision + HackerRank shell.

---

## Phase D — Cloud: AWS Deep-Dive (Weeks 11–14)

### Week 11 — AWS Core I: IAM, VPC, EC2, S3

- **Objectives:** understand the AWS "shape" and operate core services via CLI; zero console-clicking habit
- **Topics:** accounts/regions/AZs, IAM (users, groups, roles, policies, least privilege, MFA), VPC (subnets, route tables, internet gateway, NAT, security groups vs NACLs), EC2 (instances, AMIs, key pairs, user-data), S3 (buckets, versioning, lifecycle, static hosting, presigned URLs), billing alarms FIRST
- **Practice:** create the AWS Free Tier account (if you have one already, use a fresh region); set up MFA + budget alarm on day 1; do everything via aws cli
- **Mini project:** "Tiny Web Farm": VPC with public/private subnets, EC2 behind a security group, S3 for static assets, all created via CLI
- **Reading:** AWS Skill Builder free "Cloud Practitioner Essentials" (free courses, digital badge)
- **Videos:** freeCodeCamp "AWS Certified Cloud Practitioner" full course (by ExamPro, updated yearly — pick the 2025/2026 version on freeCodeCamp YouTube)
- **Documentation:** docs.aws.amazon.com — IAM user guide, VPC user guide
- **Assignments:** write a 1-page "least privilege" policy walkthrough for a CI/CD role
- **Revision:** whiteboard a VPC: 2 AZs, public+private subnets, NAT — from memory
- **Checkpoint:** create a locked-down S3 bucket + IAM policy from CLI, no console
- **Time estimate:** 35–40 hours
- **Expected outcome:** AWS feels like a programmable system, not a mystery

**Daily suggestions:** Mon: account + regions + billing alarm. Tue: IAM deep. Wed: VPC networking. Thu: EC2 + SSH. Fri: S3 + CLI. Sat: Tiny Web Farm project. Sun: revision + cost check (must be $0).

### Week 12 — AWS Core II: RDS, Lambda, CloudWatch, ALB, Autoscaling

- **Objectives:** managed services, serverless basics, and the reliability mechanics of the cloud
- **Topics:** RDS (PostgreSQL), DynamoDB, Lambda (functions, triggers, IAM roles for functions), CloudWatch (logs, metrics, alarms, dashboards), ALB + target groups, auto scaling groups (launch templates, policies), SQS/SNS basics, Route 53 (record types, failover idea)
- **Practice:** extend Tiny Web Farm: add RDS + connect the Flask app; add ALB + autoscaling
- **Mini project:** "Auto-Scale Site": Flask app on 2 AZs behind ALB, autoscaling 2–4 instances, CloudWatch alarm that triggers scale-in; terminate an instance to prove self-healing
- **Reading:** AWS Skill Builder free "Cloud Architecting" essentials modules
- **Videos:** freeCodeCamp AWS course continued; "AWS Certified Solutions Architect Associate" freeCodeCamp course (Andrew Brown) for the SAA content around autoscaling
- **Assignments:** CloudWatch alarm + SNS notification walkthrough in notes
- **Revision:** explain Lambda cold starts + scaling in 5 minutes
- **Checkpoint:** scale in/out triggered by load you generated (stress test with a loop of curl or ab)
- **Time estimate:** 35–40 hours
- **Expected outcome:** you can build resilient, self-healing cloud systems on free tier

**Daily suggestions:** Mon: RDS + security. Tue: Lambda + IAM. Wed: CloudWatch. Thu: ALB. Fri: autoscaling. Sat: Auto-Scale Site project. Sun: stress test + revision + cost check.

### Week 13 — Cloud Architecture Thinking + Serverless Patterns

- **Objectives:** think in architecture; answer "why this shape?" in interviews
- **Topics:** 3-tier architecture, stateless vs stateful, scaling (vertical vs horizontal), availability zones vs regions, RTO/RPO and backup basics, serverless vs containers decision, event-driven patterns (S3 event → Lambda → SQS → worker), cost-first design, well-architected framework pillars (free, wellarchitectedlabs.com)
- **Practice:** redesign Week 12 project as serverless (S3 + API Gateway + Lambda + DynamoDB) — the "no servers" variant
- **Mini project:** "Event Pipeline": S3 upload event → Lambda → SQS → second Lambda worker → logs to CloudWatch (dead-letter queue included)
- **Reading:** AWS Well-Architected Framework whitepaper (free)
- **Videos:** AWS events channel or freeCodeCamp SAA content on architecture patterns
- **Assignments:** whiteboard 3 architectures (3-tier, serverless event, monolith) with pros/cons
- **Revision:** write "cost analysis of my free-tier stack" — prove it costs $0
- **Checkpoint:** explain the Event Pipeline flow with failure handling, from memory
- **Time estimate:** 30–35 hours
- **Expected outcome:** architecture conversations become natural; you have a second major project

**Daily suggestions:** Mon: 3-tier + stateless principles. Tue: serverless concepts. Wed: event-driven + DLQ. Thu: well-architected pillars. Fri: build Event Pipeline. Sat: polish + docs + diagram. Sun: revision + cost check.

### Week 14 — Cloud Networking, Security, and the Second Cloud Map

- **Objectives:** cloud security posture + transferable knowledge of Azure/GCP for interview questions
- **Topics:** AWS: cross-account roles, S3 bucket policies + ACLs vs policy, VPC endpoints, SSM vs SSH, KMS basics, CloudTrail; Azure quick map (resource groups, VNet, AKS, Entra ID) and GCP quick map (projects, VPC, GKE, IAM) — 1 day each
- **Practice:** enable CloudTrail, review an access audit; set up AWS SSM Session Manager access instead of SSH
- **Mini project:** "Locked-Down Account": a written + applied security checklist (MFA, no root keys, least privilege, encryption, trail) applied to your account; screenshot as evidence
- **Reading:** AWS Security best practices docs; Microsoft Learn free "Azure fundamentals" path (audit mode)
- **Videos:** freeCodeCamp "Azure Fundamentals" or "Google Cloud Digital Leader" free courses (pick one, 2–3 days)
- **Assignments:** build a comparison table: AWS vs Azure vs GCP core services (compute, db, k8s, function, iam, monitoring)
- **Revision:** quiz yourself on security group vs NACL vs IAM policy — the classic interview triple
- **Checkpoint:** answer "how would you secure a new AWS account?" in 3 minutes from memory
- **Time estimate:** 30–35 hours
- **Expected outcome:** security-aware cloud operator with credible multi-cloud awareness

**Daily suggestions:** Mon: S3 security + CloudTrail. Tue: KMS + SSM. Wed: Azure map. Thu: GCP map. Fri: comparison table. Sat: Locked-Down Account project. Sun: revision + LeetCode batch.

---

## Phase E — IaC & Config Management (Weeks 15–17)

### Week 15 — Terraform Core

- **Objectives:** provision infrastructure as code, reproducibly
- **Topics:** terraform init/plan/apply/destroy, providers, resources, data sources, variables, locals, outputs, dependencies, terraform fmt/validate, lifecycle rules, tags everywhere
- **Practice:** rewrite your Week 11 Tiny Web Farm as Terraform — delete the console/CLI-created one first (proving reproducibility)
- **Mini project:** "TF Web Farm": VPC + subnets + EC2 + S3 + security groups, 100% Terraform, with variables
- **Reading:** HashiCorp Learn Terraform track (developer.hashicorp.com/terraform/tutorials) — the first 10 tutorials
- **Videos:** TechWorld with Nana "Terraform Tutorial for Beginners" (the 3h course) or freeCodeCamp "Terraform" course
- **Assignments:** destroy and re-apply the whole stack in one command chain; prove zero drift
- **Revision:** explain the plan/apply cycle and why state exists
- **Checkpoint:** change a variable, plan shows only the expected diff — no surprises
- **Time estimate:** 35–40 hours
- **Expected outcome:** the #2 highest-leverage skill, demonstrably applied

**Daily suggestions:** Mon: basics + init/plan. Tue: resources + data sources. Wed: variables + outputs. Thu: state + destroy. Fri: fmt/validate + tags. Sat: TF Web Farm project. Sun: revision + re-apply everything from scratch.

### Week 16 — Terraform Advanced: State, Modules, Backends

- **Objectives:** team-grade Terraform: remote state, locking, modules
- **Topics:** state deep-dive (what's in it, why sensitive), remote state in S3 + DynamoDB locking, workspaces, modules (write + publish own), terraform import, drift detection, sensitive values, checkov policy checks, terragrunt awareness
- **Practice:** create a state S3 bucket + DynamoDB lock table via Terraform; migrate local state to remote
- **Mini project:** "TF Platform": a small module library (network module, compute module, storage module) with versioned releases, used by a root stack
- **Reading:** HashiCorp Learn — "State" and "Modules" tracks; Terraform Best Practices site (terraform-best-practices.com)
- **Videos:** freeCodeCamp "Terraform Modules" content or Nana's advanced episodes
- **Assignments:** refactor Week 15 project to use your own modules; run checkov and fix findings
- **Revision:** write "what happens when two engineers terraform apply at the same time?"
- **Checkpoint:** demo team workflow: two "engineers" (two shells) with state locking, one applies, the other waits
- **Time estimate:** 35–40 hours
- **Expected outcome:** your IaC is as professional as most mid-level teams'

**Daily suggestions:** Mon: state deep-dive. Tue: remote state + locking. Wed: modules part 1. Thu: modules part 2 + versions. Fri: import + drift + checkov. Sat: TF Platform project. Sun: revision + locking demo.

### Week 17 — Ansible + Secrets Management + Packer Awareness

- **Objectives:** configure after provision; manage secrets; bake images
- **Topics:** Ansible: inventory, playbooks, modules, handlers, variables, templates (Jinja2), tags, idempotency, ad-hoc; secrets: SSH keys, env files, Vault awareness (HashiCorp Vault: basic concepts, AppRole, dynamic secrets), never-in-git rules; Packer: what it does, awareness level
- **Practice:** use Ansible (local mode or against your VM) to configure the Flask app server: install deps, deploy artifact, restart service — run it 3x, prove idempotency
- **Mini project:** "Config Stack": Ansible playbook + roles that deploy and configure your Flask app across 2 hosts, with secrets pulled from environment (and a note on Vault)
- **Reading:** Ansible docs (docs.ansible.com) getting-started; Jeff Geerling's Ansible role examples (github.com/geerlingguy)
- **Videos:** Jeff Geerling "Ansible 101" series on YouTube (free, the canonical series)
- **Assignments:** write a role that installs Docker + a hardened SSH config, run twice
- **Revision:** explain "Terraform vs Ansible" — the interview classic
- **Checkpoint:** idempotency demo: second run changes nothing, exit says ok=unchanged
- **Time estimate:** 30–35 hours
- **Expected outcome:** full provision+configure capability; you can answer config-management interviews

**Daily suggestions:** Mon: inventory + ad-hoc. Tue: playbooks + modules. Wed: handlers + templates. Thu: roles. Fri: secrets + Vault concepts. Sat: Config Stack project. Sun: revision + write Terraform-vs-Ansible essay.

---

## Phase F — Kubernetes & GitOps (Weeks 18–21)

### Week 18 — Kubernetes Core

- **Objectives:** cluster mental model + day-1 workload operations
- **Topics:** architecture (control plane: API server, etcd, scheduler, controller manager; nodes: kubelet, kube-proxy, container runtime), kubectl essentials (get, describe, logs, exec, port-forward, apply/delete), pods, deployments, replicasets, services (ClusterIP, NodePort, LoadBalancer), labels & selectors, namespaces, probes (liveness/readiness/startup)
- **Practice:** install kind (or minikube); deploy and scale apps; break and heal (delete pods, watch recreation)
- **Mini project:** "First Cluster": deploy the Flask app with a Deployment (3 replicas) + Service + probes; simulate a crash and watch self-healing
- **Reading:** kubernetes.io/docs tutorials — "Learn Kubernetes Basics" interactive modules
- **Videos:** TechWorld with Nana "Kubernetes Tutorial for Beginners [FULL COURSE in 4 Hours]" — the canonical free course
- **Interactive:** Killercoda Kubernetes scenarios (killercoda.com) — free browser labs
- **Assignments:** 20 kubectl drills: describe, edit, rollout status, rollout undo
- **Revision:** whiteboard cluster architecture from memory (control plane vs nodes)
- **Checkpoint:** roll out a bad image, roll back, explain what you saw
- **Time estimate:** 40–45 hours
- **Expected outcome:** the hardest skill on the market is no longer mysterious

**Daily suggestions:** Mon: architecture + kind. Tue: pods + deployments. Wed: services + labels. Thu: probes + namespaces. Fri: kubectl power skills. Sat: First Cluster project. Sun: revision + whiteboard from memory.

### Week 19 — Kubernetes Config, Storage, and Day-2 Operations

- **Objectives:** configuration management, storage, and production operations inside clusters
- **Topics:** configmaps, secrets (base64, SOPS/External Secrets awareness), PV/PVC + storage classes, requests/limits and QoS, HPA (metrics-server), node affinity/tolerations, taints, updates (rolling, maxSurge/maxUnavailable), cordon/drain, ClusterIP vs DNS (service discovery), Ingress + ingress-nginx
- **Practice:** convert your Flask app to use ConfigMaps + Secrets + PVC for uploads; enable HPA with load test
- **Mini project:** "Production-ish Cluster": app with config, secrets, persistent storage, HPA, ingress with TLS (self-signed or cert-manager on real domain)
- **Reading:** Kubernetes docs — Configuration, Storage, Workloads sections
- **Videos:** "Kubernetes for the Absolute Beginners" labs via Killercoda; or Nana's Day-2 episodes
- **Assignments:** write a troubleshooting runbook: CrashLoopBackOff, ImagePullBackOff, Pending, OOMKilled — one page each
- **Revision:** explain requests vs limits and why they matter for scheduling
- **Checkpoint:** diagnose a deliberately broken deployment (crash loop + pending pod) in <10 minutes using only kubectl
- **Time estimate:** 40–45 hours
- **Expected outcome:** you can run a realistic workload on K8s and debug it

**Daily suggestions:** Mon: configmaps + secrets. Tue: storage. Wed: limits + HPA. Thu: scheduling + taints. Fri: ingress + TLS. Sat: Production-ish Cluster project. Sun: runbook writing + revision.

### Week 20 — Helm + GitOps with ArgoCD

- **Objectives:** package apps with Helm; deploy with GitOps so the cluster reflects Git exactly
- **Topics:** Helm: charts, values.yaml, templates, chart structure, helm create/install/upgrade/rollback, dependencies, release management; ArgoCD: apps, projects, sync strategies, self-healing, health checks, the GitOps pattern (repo = desired state), ArgoCD CLI + UI
- **Practice:** convert your app into a Helm chart with env-based values; install ArgoCD on kind; register your Git repo as the source of truth
- **Mini project:** "GitOps Cluster": app deployed ONLY through git commits → ArgoCD auto-sync; make a change, revert it, watch self-healing fight the drift
- **Reading:** helm.sh docs — Charts guide; argoproj.github.io/cd docs — Getting Started
- **Videos:** TechWorld with Nana "Helm Tutorial" and "ArgoCD Tutorial" (both exist and are current on her channel)
- **Assignments:** document "desired state vs observed state" in your own words with an example
- **Revision:** explain why GitOps beats kubectl apply in teams
- **Checkpoint:** demonstrate: git commit → cluster changes in <60 seconds, no kubectl involved
- **Time estimate:** 40–45 hours
- **Expected outcome:** you practice GitOps exactly as modern teams do — a top interview talking point

**Daily suggestions:** Mon: Helm basics. Tue: Helm templating. Wed: ArgoCD install + app. Thu: sync policies + self-healing. Fri: drift war (kill drift, watch heal). Sat: GitOps Cluster project. Sun: revision + essay on GitOps.

### Week 21 — Kubernetes in Production: Security, Scaling, Troubleshooting

- **Objectives:** the "what could go wrong" expertise that separates juniors
- **Topics:** RBAC (roles, bindings, service accounts), pod security (PSA), network policies (Calico/Cilium awareness), resource limits enforcement, cluster upgrades, backup (etcd snapshots, Velero awareness), kubectl debugging toolbox (kubectl debug, ephemeral containers), k9s, logs: kubectl logs --previous, events, taints/cordons during maintenance
- **Practice:** run network policy demos; break the cluster deliberately (scale down deployments, delete etcd-backed objects) and recover
- **Mini project:** "Battle-Tested Cluster": hardening checklist applied + a 10-page troubleshooting runbook + a chaos test (kill pods, kill nodes, drain) with documented results
- **Reading:** Kubernetes docs — RBAC, Network Policies, Pod Security
- **Videos:** Killercoda advanced scenarios; "Kubernetes Troubleshooting" by David McKay (raesene?) or Red Hat's free K8s troubleshooting webinars
- **Assignments:** write a runbook entry for "pod stuck Pending" end-to-end with a real reproduction
- **Revision:** security quiz: which defaults are unsafe in a default cluster?
- **Checkpoint:** fix a broken cluster scenario on Killercoda under time pressure
- **Time estimate:** 40–45 hours
- **Expected outcome:** you can keep a cluster alive and explain how — massive interview confidence

**Daily suggestions:** Mon: RBAC + SA. Tue: pod security + policies. Wed: network policies. Thu: upgrades + backups. Fri: debugging toolbox. Sat: Battle-Tested Cluster project + chaos. Sun: runbook polish + revision.

---

## Phase G — Reliability & DevSecOps (Weeks 22–23)

### Week 22 — Observability: Prometheus, Grafana, Loki, OpenTelemetry

- **Objectives:** measure everything; prove reliability with SLOs — the highest-paying skill tier
- **Topics:** metrics vs logs vs traces; Prometheus: targets, exporters (node_exporter, cAdvisor), service discovery, PromQL (rate, histogram_quantile), recording rules; Alertmanager routing; Grafana dashboards (variables, panels, alerts); Loki for logs (label-based); OpenTelemetry: what traces/metrics/logs are, SDK + OTLP concepts, why it's the standard; SLOs/SLIs and error budgets
- **Practice:** deploy Prometheus + Grafana on your kind cluster (kube-prometheus-stack helm chart); add node + app exporters; build dashboards for your Flask app; trigger an alert
- **Mini project:** "Reliability Dash": SLO dashboard (availability 99.5% error budget burn-down) for your app, with alert on budget exhaustion + a Loki log view
- **Reading:** prometheus.io/docs — getting started; grafana.com/docs; opentelemetry.io/docs; Google SRE book ch. on SLOs (free, sre.google)
- **Videos:** TechWorld with Nana "Prometheus Monitoring" and "Grafana" courses; Google SRE "Introduction to SRE" (free YouTube)
- **Assignments:** define an SLO for your app in writing: SLI formula + error budget policy
- **Revision:** explain the difference between monitoring and observability
- **Checkpoint:** point to your dashboard, explain 3 panels (requests, latency, errors) and one alert — 3 minutes
- **Time estimate:** 35–40 hours
- **Expected outcome:** the premium $145–160K skill tier is on your resume with real evidence

**Daily suggestions:** Mon: metrics + Prometheus setup. Tue: PromQL + exporters. Wed: alerting. Thu: Grafana dashboards. Fri: Loki + OpenTelemetry. Sat: Reliability Dash project. Sun: SLO write-up + revision.

### Week 23 — DevSecOps: Security in the Pipeline

- **Objectives:** bake security into every stage; pass security-flavored interviews
- **Topics:** shift-left security; SAST (Semgrep — free, linter-style) vs DAST (OWASP ZAP basics) vs SCA (dependency scanning); container scanning (trivy in CI); secret scanning (gitleaks); IaC scanning (checkov); SBOM awareness; OWASP Top 10; supply-chain hygiene (lock files, pinned images, trusted sources); principle of least privilege in pipelines
- **Practice:** add Semgrep + gitleaks + trivy + checkov to your Uni-Pipeline as separate jobs that fail the build on findings
- **Mini project:** "Secure Pipeline": the full suite — every commit scanned; a documented "what each scanner catches" matrix; a deliberately vulnerable test file that gets caught
- **Reading:** OWASP Top 10 (owasp.org) — the web version; checkov docs; gitleaks docs
- **Videos:** freeCodeCamp "DevSecOps" course (by Dina/Marufa?) or TryHackMe free DevSecOps path (tryhackme.com — free tier rooms)
- **Assignments:** run a full scan sweep on all your repos; fix or document every finding
- **Revision:** explain "shift left" and name 3 scanners and what each catches
- **Checkpoint:** demo a pipeline failing on a security finding, fix, re-green
- **Time estimate:** 30–35 hours
- **Expected outcome:** DevSecOps awareness — a durable, premium, compliance-driven skill

**Daily suggestions:** Mon: SAST + Semgrep. Tue: secrets + gitleaks. Wed: IaC + checkov. Thu: DAST + ZAP basics. Fri: supply chain + SBOM. Sat: Secure Pipeline project. Sun: vulnerability sweep + revision.

---

## Phase H — Launch (Week 24)

### Week 24 — Portfolio Polish, Interview Drills, and First Applications

- **Objectives:** package everything into hire-ready artifacts; start the job search engine
- **Topics:** resume rewrite (Part 9), GitHub profile optimization (Part 8), LinkedIn upgrade (Part 10), portfolio site live, capstone README + demo video, mock interviews (Part 11), application funnel setup (Part 13)
- **Practice:** record a 5-minute demo of your capstone; do 5 mock interviews (with AI or a friend); apply to 10 jobs daily
- **Mini project:** the application system: Notion/Excel tracker, resume PDF per target role, cold-outreach templates
- **Reading:** rerun your own notes — a full self-review week
- **Videos:** mock interview replays on YouTube ("DevOps interview questions" channels) — watch 3, critique yourself
- **Assignments:** complete the Final Success Checklist (Part 20)
- **Revision:** full self-audit against the MUST skills list; patch gaps in 60-min blocks
- **Checkpoint:** you can answer 20 of the top interview questions without notes
- **Time estimate:** 35–40 hours (plus application time)
- **Expected outcome:** complete job-search machine running: profile, resume, portfolio, interviews, applications — with live evidence of every skill

**Daily suggestions:** Mon: resume + LinkedIn. Tue: portfolio site + capstone README. Wed: demo video + GH profile. Thu: mock interviews x2. Fri: apply 10 + track. Sat: apply 10 + outreach. Sun: review funnel + plan next week.
---

# Part 4 — Best Completely Free Resources

Curated, currently maintained, and ordered by how essential they are. If a link dies, search the title on Google/YouTube — every resource below has active mirrors.

## Linux

- **Official documentation:** Ubuntu Server Guide (ubuntu.com/server/docs); man pages (man7.org)
- **Best YouTube playlist:** Learn Linux TV — "Linux Crash Course" series (youtube.com/@LearnLinuxTV) — short attackable episodes
- **Best YouTube course:** freeCodeCamp "The Linux Command Line Bootcamp" (freeCodeCamp YouTube — pick the newest)
- **GitHub repositories:** tldr-pages/tldr (community cheatsheets); jlevy/the-art-of-command-line (single-file masterclass)
- **Interactive:** Linux Journey (linuxjourney.com); OverTheWire Bandit (overthewire.org/wargames/bandit)
- **Free book:** The Linux Command Line, William Shotts — free PDF at linuxcommand.org/tlcl.php (the single best free Linux book)
- **Cheat sheet:** awesome-linux (github.com/inputsh/awesome-linux); tldr command
- **Practice:** HackerRank Linux Shell track; killercoda Linux scenarios (killercoda.com)
- **Community:** r/linuxadmin, r/linux, Ubuntu forums; Discord: Linux Atlas / Ubuntu community servers

## Git & GitHub

- **Official documentation:** git-scm.com/doc; Pro Git book free at git-scm.com/book/en/v2
- **Best YouTube course:** freeCodeCamp "Git and GitHub for Beginners — Crash Course" (updated yearly on freeCodeCamp YouTube)
- **Best YouTube playlist:** The Net Ninja "Git & GitHub Tutorial for Beginners" playlist
- **GitHub repositories:** github/gitignore; actions/starter-workflows (pipeline templates); git/git (read the docs, don't read the code)
- **Interactive:** Learn Git Branching (learngitbranching.js.org) — mandatory
- **Official labs:** GitHub Skills (skills.github.com) — free official courses with credential badges: Introduction to GitHub, Reviewing pull requests, Communicate using Markdown
- **Cheat sheet:** GitHub training kit git cheatsheet (training.github.com)
- **Community:** r/git; GitHub Discussions; Discord: The Programming Hub

## Bash Scripting

- **Official documentation:** GNU Bash manual (gnu.org/software/bash/manual); ShellCheck rules (github.com/koalaman/shellcheck)
- **Best YouTube course:** freeCodeCamp "Bash Scripting Full Course" (freeCodeCamp YouTube)
- **Best YouTube playlist:** Learn Linux TV — "Bash Scripting" tutorial series
- **GitHub repositories:** koalaman/shellcheck; sstephenson?—no—use: BashGuide at mywiki.wooledge.org/BashGuide
- **Interactive:** BashCrawl (gitlab.com/... play the roguelike)? — solid alt: Linux Journey scripting section
- **Free book:** Bash Guide, Greg's Wiki (mywiki.wooledge.org/BashGuide) — the canonical free reference
- **Practice:** HackerRank Linux Shell; Exercism Bash track (exercism.org)
- **Cheat sheet:** devhints.io/bash; explainshell.com (paste a command, get explanations)
- **Community:** r/bash, r/commandline

## Python

- **Official documentation:** Python tutorial (docs.python.org/3/tutorial)
- **Best YouTube course:** freeCodeCamp "Learn Python — Full Course for Beginners" (4h, re-published yearly)
- **Best YouTube playlist:** Corey Schafer "Python Tutorials" playlist (python basics + oop)
- **GitHub repositories:** vinta/awesome-python (curated ecosystem); practical python
- **Interactive:** Exercism Python track (exercism.org); CodeSignal arcade (free tier)
- **Free book:** Automate the Boring Stuff with Python — free online (automatetheboringstuff.com)
- **Practice:** LeetCode easy/medium; HackerRank Python track
- **Cheat sheet:** pythoncheatsheet.org
- **Community:** r/learnpython; Discord: Python Discord (pythondiscord.com)

## Docker & Containers

- **Official documentation:** docs.docker.com (getting-started tutorial is excellent)
- **Best YouTube course:** TechWorld with Nana "Docker Tutorial for Beginners [FULL COURSE in 3 Hours]" (youtube.com/@TechWorldwithNana) — the gold standard, kept current
- **Best YouTube playlist:** Nana's "Docker" playlist; Collabnix tutorials
- **GitHub repositories:** docker/example-voting-app; prakhar1989/docker-curriculum (a mini-book in a repo); Collabnix/dockerlabs
- **Interactive:** Play with Docker (labs.play-with-docker.com); Killercoda Docker scenarios
- **Free book:** Docker Curriculum (github.com/prakhar1989/docker-curriculum)
- **Practice:** build today's tasks into containers; CatContainer? no — do Killercoda scenarios
- **Cheat sheet:** dockerlabs cheat sheet (Collabnix); one-page Docker tricks
- **Community:** r/docker; Docker Community Slack (docker.com/community)

## CI/CD — GitHub Actions

- **Official documentation:** docs.github.com/actions (Learning GitHub Actions guide is complete and free)
- **Best YouTube course:** freeCodeCamp "GitHub Actions — Full Course" (freeCodeCamp YouTube, updated)
- **Best YouTube playlist:** TechWorld with Nana "GitHub Actions Tutorial" and "DevOps Bootcamp" (youtube.com/@TechWorldwithNana)
- **GitHub repositories:** actions/starter-workflows (template workflows for everything); actions/checkout; shivammathur/setup-* actions for runtimes
- **Interactive:** official GitHub Actions lab in GitHub Skills ("GitHub Actions: Write workflows")
- **Practice:** add CI to every repo you own; break it on purpose
- **Cheat sheet:** read the workflow syntax reference (docs.github.com/actions/reference)
- **Community:** r/githubactions; GitHub Community forums (github.community)

## AWS

- **Official documentation:** documents in the AWS docs hub (docs.aws.amazon.com); AWS Workshops (workshops.aws — free official hands-on labs)
- **Best YouTube course:** freeCodeCamp "AWS Certified Cloud Practitioner" full course (by ExamPro — freeCodeCamp re-uploads updated versions yearly; search "ExamPro AWS 2026")
- **Best YouTube playlist:** freeCodeCamp "AWS Certified Solutions Architect — Associate" course + Be a Better Dev AWS playlists
- **GitHub repositories:** aws/aws-cdk-examples; aws/containers-roadmap (trending signals); Don't-Read-only: aws/aws-cli docs
- **Interactive:** AWS Skill Builder free tier (explore.skillbuilder.aws) — official free courses + digital badges; AWS Educate (aws.amazon.com/education)
- **Free book:** "AWS in Action" free sample? no — official whitepapers: Well-Architected Framework (docs.aws.amazon.com/wellarchitected) are the best free AWS reading
- **Practice:** AWS free tier hands-on; AWS CloudQuest (free samples in Skill Builder)
- **Cheat sheet:** awscli cheatsheet (github.com/aws-cli, community docs); Serverless Land (serverlessland.com) patterns
- **Community:** r/aws, r/awsdevops; AWS community Discord (awsdevelopers.io); AWS User Groups local

## Terraform

- **Official documentation:** developer.hashicorp.com/terraform (tutorials = full free course)
- **Best YouTube course:** TechWorld with Nana "Terraform Tutorial for Beginners" (youtube.com/@TechWorldwithNana)
- **Best YouTube playlist:** freeCodeCamp "Terraform" course; Anton Putra Terraform episodes
- **GitHub repositories:** awesome-iac? no — use: terraform-aws-modules (the standard modules); bridgecrewio/checkov (scanner); HashiCorp official example repos
- **Interactive:** HashiCorp Learn tutorials with in-browser terminal (developer.hashicorp.com/terraform/tutorials)
- **Free book:** Terraform Up & Running, Yevgeniy Brikman — official free chapters at terraformupandrunning.com (ch. 1–2 + selected chapters)
- **Practice:** re-create every AWS lab in Terraform; break and fix state
- **Cheat sheet:** terraform cheat sheet (community, search "terraform cheatsheet" on GitHub)
- **Community:** r/Terraform; HashiCorp Discuss (discuss.hashicorp.com); Discord: HashiCorp community

## Ansible

- **Official documentation:** docs.ansible.com (excellent getting-started)
- **Best YouTube series:** Jeff Geerling "Ansible 101" (youtube.com/@JeffGeerling) — the canonical free series
- **GitHub repositories:** geerlingguy/ansible-for-devops (examples); geerlingguy/ansible-role-* (production roles to study)
- **Free book:** Ansible for DevOps (geerlingguy.com) — source examples free on GitHub; read on his blog
- **Practice:** configure your own VMs twice, prove idempotency
- **Community:** r/ansible; Ansible forum (forum.ansible.com)

## Kubernetes

- **Official documentation:** kubernetes.io/docs + interactive "Learn Kubernetes Basics" tutorial modules (kubernetes.io/docs/tutorials/kubernetes-basics)
- **Best YouTube course:** TechWorld with Nana "Kubernetes Tutorial for Beginners [FULL COURSE in 4 Hours]" — still the #1 free K8s launchpad
- **Best YouTube playlist:** "Kubernetes for Developers" by Nana; freeCodeCamp K8s courses; Kubernetes Official channel (youtube.com/@KubernetesCommunity) — KubeCon talks for depth
- **GitHub repositories:** kelseyhightower/kubernetes-the-hard-way (understand EVERYTHING; do the kind/minikube community edition variants, not real clouds); kubernetes/examples (canonical YAML); kubernetes/minikube
- **Interactive:** Killercoda Kubernetes scenarios (killercoda.com) — free browser labs; Play with Kubernetes (labs.play-with-k8s.com)
- **Free book:** Kubernetes Up & Running (O'Reilly) — free chapters on authors' site (kubernetesupandrunning.com); also the official "101" docs
- **Practice:** kind clusters, chaos pods, broken-cluster recovery drills
- **Cheat sheet:** kubectl cheatsheet (kubernetes.io/docs/reference/kubectl/cheatsheet) — official
- **Community:** r/kubernetes; Kubernetes Slack (slack.k8s.io); CNCF Community Slack (community.cncf.io — join waiting lists early, they matter for networking)

## Helm & GitOps

- **Official documentation:** helm.sh/docs; argoproj.github.io/cd (ArgoCD); fluxcd.io (Flux) — docs of both are free courses
- **Best YouTube:** TechWorld with Nana "Helm Tutorial" and "ArgoCD Tutorial" (channel kept current)
- **GitHub repositories:** helm/helm; argoproj/argo-cd; bitnami/charts (study real charts); helm/charts archives in bitnami
- **Practice:** convert apps to charts; synch/drift drills with ArgoCD
- **Community:** r/ArgoCD; CNCF K8s Slack #argo-cd channel

## Observability

- **Official documentation:** prometheus.io/docs; grafana.com/docs; opentelemetry.io/docs; sre.google (free Google SRE books)
- **Best YouTube courses:** TechWorld with Nana "Prometheus Monitoring — with Grafana" and "Grafana" courses; Google "Site Reliability Engineering" intro course (free, sre.google/static? no — YouTube "Introduction to SRE" by Google)
- **GitHub repositories:** prometheus-operator/kube-prometheus (the stack); grafana/dashboards (community dashboards); Thanos/Cortex awareness
- **Interactive:** PromLabs PromQL interactive tutorial (promlabs.com/promql/ — "Query Examples" interactive); grafana.com/learn
- **Free book:** Google SRE book (sre.google/books) — free, three volumes
- **Cheat sheet:** PromQL cheatsheet (community)
- **Community:** r/PrometheusMonitoring? (small) — better r/grafana; Grafana community (community.grafana.com); OTEL slack

## DevSecOps / Security

- **Official documentation:** OWASP Top 10 (owasp.org); checkov docs; trivy docs (aquasecurity.github.io/trivy); Semgrep docs; gitleaks docs
- **Best YouTube:** freeCodeCamp "DevSecOps" courses; "TryHackMe" free rooms for security basics (tryhackme.com free tier)
- **GitHub repositories:** bridgecrewio/checkov; aquasecurity/trivy; gitleaks/gitleaks; OWASP/CheatSheetSeries
- **Practice:** scan your own repos; break your own pipeline on purpose
- **Community:** r/netsec (read), r/cybersecurity; OWASP local chapters

## DevOps Big-Picture / Career-Long

- **GitHub repositories:** MichaelCade/90DaysOfDevOps (free 90-day curriculum repo with curated videos); bregman-arie/devops-exercises (THE interview question bank + learning asset — 10k+ questions); zero-to-mastery? no. Also: bregman-arie/devops-resources (curated resources)
- **Best YouTube channel:** freeCodeCamp.org (publishes updated full DevOps stacks yearly); TechWorld with Nana; Learn Linux TV; Jeff Geerling; Devon? no. "DevOps Directive" for advanced interviews
- **Podcasts:** Kubernetes Podcast (kubernetespodcast.com); Ship It (changelog.com/shipit); Screaming in the Cloud (screaminginthecloud.com)
- **Newsletters (free):** DevOps Weekly (devopsweekly.com); DevOps'ish (devopsish.com); KubeWeekly (kubeweekly.io); ByteByteGo newsletter (blog.bytebytego.com — system design explainers); cncf.io/blog RSS
- **Reddit:** r/devops, r/kubernetes, r/Terraform, r/aws, r/selfhosted, r/homelab (homelab builds are legitimate resume evidence)
- **Discord/Slack:** CNCF Slack (community.cncf.io); Kubernetes Slack (slack.k8s.io); AWS Developers Discord; "DevOps & Cloud Native" Discords (search "devops discord invite" — several large active ones)
- **Forums:** HashiCorp Discuss; GitLab Forum? (gitlab.com forum); Ansible Forum; Stack Overflow tags devops/docker/kubernetes/terraform
- **Interview prep:** bregman-arie/devops-exercises; "DevOps Interview Preparation" blogs (search latest); Pramp (pramp.com — free peer mock interviews)

---

# Part 5 — Free Certifications

Reality check first: **2026 hiring is skills-based.** TestGorilla's State of Skills-Based Hiring: 53% of employers removed degree requirements from some postings; hiring for skills is ~5x more predictive than education. Certificates open some doors (especially in India/enterprise/consultancies); **projects and deployed systems open more.** Do these in order: free ones first, exams only when you can afford them and they matter for your target market.

## Tier 1 — 100% free certificates (earn now)

### 1. freeCodeCamp Relational Database Certification
- **Provider:** freeCodeCamp | **Difficulty:** easy-medium | **Industry value:** low (but teaches SQL + Bash + Linux + Git basics for free, which you need anyway)
- **Time:** 20–40 hours | **Link:** freecodecamp.org/learn/relational-database
- **Recruiters value it:** marginally — do it because it structures Weeks 1–5 content
- **Beginner-friendly:** YES — first thing to earn

### 2. GitHub Skills credentials
- **Provider:** GitHub (official) | **Difficulty:** easy | **Industry value:** small but official and free; badges live on your GitHub profile
- **Time:** 10–15 hours for 5 courses | **Link:** skills.github.com
- **Recruiters value it:** barely — do it for the official hands-on practice (Introduction to GitHub, GitHub Pages, GitHub Actions)
- **Beginner-friendly:** YES

### 3. IBM SkillsBuild — DevOps & Cloud Essentials
- **Provider:** IBM | **Difficulty:** easy | **Industry value:** low-moderate outside India
- **Time:** 10–20 hours | **Link:** skillsbuild.org (search "DevOps")
- **Recruiters value it:** low — but free, official, and quick; good early confidence + LinkedIn badge
- **Beginner-friendly:** YES

### 4. AWS Skill Builder free courses + digital badges
- **Provider:** AWS (official) | **Difficulty:** easy-medium | **Industry value:** moderate — official AWS content
- **Time:** 15–25 hours (free tier: Cloud Practitioner Essentials + select badge courses) | **Link:** explore.skillbuilder.aws (free tier)
- **Recruiters value it:** low-moderate (badges), but the knowledge directly feeds Week 11–14 and the paid exam below later
- **Beginner-friendly:** YES

### 5. Linux Foundation free courses (edX)
- **Provider:** The Linux Foundation via edX (audit-track free) | **Difficulty:** easy-medium | **Industry value:** moderate (official Linux training)
- **Time:** 20–30 hours | **Link:** edx.org — "Introduction to Linux" (LFS101x) — audit for free
- **Recruiters value it:** moderate in enterprise/India
- **Beginner-friendly:** YES

### 6. CNCF — "Introduction to Kubernetes" (edX audit) + Kubernetes Community Days free content
- **Provider:** CNCF via edX (LFS158x) | **Difficulty:** medium | **Time:** 15–20 hours | **Link:** edx.org — audit free
- **Recruiters value it:** moderate — CNCF is THE cloud-native brand
- **Beginner-friendly:** Yes, with Week 18 practice

### 7. Cisco Networking Academy — DevNet Associate (self-paced, free enrollment)
- **Provider:** Cisco | **Difficulty:** medium | **Time:** 30–40 hours | **Link:** netacad.com
- **Recruiters value it:** low-moderate — but the networking fundamentals content is excellent for Part 2 skill #14
- **Beginner-friendly:** Yes

### 8. Microsoft Learn free learning paths (no cert, but official)
- **Provider:** Microsoft | **Difficulty:** easy | **Time:** 10–20 hours | **Link:** learn.microsoft.com — "Azure Fundamentals" path (free, exam optional)
- **Recruiters value it:** content only — but free official on-demand labs for the Azure map (Week 14)
- **Beginner-friendly:** Yes

## Tier 2 — Free to learn; exam costs money (only if/when it pays for itself)

These are NOT free to certify. Listed honestly with true exam prices so you can plan; skip them if budget is zero — they are never required for your first job.

### 9. AWS Certified Cloud Practitioner (exam ~$100)
- **Why later:** the resume signal US recruiters recognize most for entry-level cloud/DevOps; also pairs with your free tier work
- **Order suggestion:** after Week 12 content. Use freeCodeCamp/ExamPro free prep course.
- **Recruiters value it:** moderate-high for entry roles (esp. managed service providers, consultancies, India service-based companies)

### 10. HashiCorp Certified: Terraform Associate (exam ~$70)
- **Why later:** proof of IaC; directly maps to Week 15–16; free prep on HashiCorp Learn
- **Recruiters value it:** moderate; valuable on Indian/MSP resumes

### 11. CKA — Certified Kubernetes Administrator (~$395) / CKAD (~$395)
- **Why later (Year 1–2, job-funded):** the strongest DevOps credential; killercoda free labs prepare you. Never before your first job.
- **Recruiters value it:** high for K8s roles, but absurd to pay for before employment

### 12. Google Professional Cloud DevOps Engineer (~$125) / Azure DevOps Engineer Expert (~$165)
- **Why later:** only if you target those clouds. Free learning paths exist for both (cloud.google.com/learn, learn.microsoft.com).

## Suggested order (this roadmap)

1. GitHub Skills credentials (W3) → 2. Linux Foundation LFS101x audit (W1–2) → 3. freeCodeCamp Relational DB (W5) → 4. AWS Skill Builder badge (W11) → 5. CNCF K8s intro audit (W18) → 6. [funded] AWS CP (W12+) → 7. [funded] Terraform Associate (W16+) → 8. [funded, Year 2] CKA

**Rule:** a certificate on LinkedIn without a live project behind it hurts your credibility. Every certificate above must be paired with a repo in your profile the same week.

---

# Part 6 — Complete Tool Stack

| # | Tool | Purpose | Free alternative | Install | Docs |
|---|---|---|---|---|---|
| 1 | WSL2 + Ubuntu | Linux on Windows | native Linux live USB | learn.microsoft.com/windows/wsl/install | ubuntu.com/wsl |
| 2 | VS Code + Remote-SSH + Dev Containers | editor + remote work | — | code.visualstudio.com | code.visualstudio.com/docs |
| 3 | Git / GitHub / gh | version control, portfolio, CI | GitLab | git-scm.com/downloads; cli.github.com | git-scm.com/doc |
| 4 | Bash 5 + coreutils | scripting | — | ships with WSL | gnu.org/software/bash/manual |
| 5 | Python 3 + venv | automation | — | python.org/downloads | docs.python.org |
| 6 | Docker Engine / Desktop | containers | Podman (podman.io) | docs.docker.com/engine/install | docs.docker.com |
| 7 | docker compose | multi-container | podman-compose | bundled with Docker | docs.docker.com/compose |
| 8 | Docker Hub / GHCR | registries | GHCR (free with GitHub) | — | ghcr.io docs |
| 9 | GitHub Actions | CI/CD | GitLab CI free tier | — | docs.github.com/actions |
| 10 | trivy | container scanning | — | aquasecurity.github.io/trivy | same |
| 11 | AWS free tier + aws cli | cloud practice | Oracle Cloud Always Free / localstack | aws.amazon.com/free; aws cli docs | docs.aws.amazon.com/cli |
| 12 | localstack (if AWS unavailable) | local AWS emulation | — | docs.localstack.cloud | same |
| 13 | Terraform | IaC | OpenTofu (opentofu.org) | developer.hashicorp.com/terraform/install | developer.hashicorp.com/terraform/docs |
| 14 | checkov / tfsec | IaC security | checkov is free | github.com/bridgecrewio/checkov | docs |
| 15 | Ansible | config management | — | docs.ansible.com/ansible/latest/installation_guide | docs |
| 16 | kind / minikube / k3s | local K8s | all free | kind.sigs.k8s.io; minikube.sigs.k8s.io | kubernetes.io/docs |
| 17 | kubectl + k9s | cluster control | — | kubernetes.io/docs/tasks/tools | same |
| 18 | Helm | K8s packaging | — | helm.sh/docs/intro/install | helm.sh/docs |
| 19 | ArgoCD / Flux | GitOps | both free/OSS | argoproj.github.io/cd; fluxcd.io | docs |
| 20 | Prometheus + Grafana + Loki | observability | — (free OSS) | prometheus.io; grafana.com | docs |
| 21 | OpenTelemetry collector | telemetry standard | — | opentelemetry.io/docs | same |
| 22 | Semgrep + gitleaks + ShellCheck | pipeline security/lint | all free OSS | semgrep.dev; gitleaks.io; shellcheck.net | docs |
| 23 | jq / yq | JSON/YAML CLI | — | jqlang.github.io/jq; mikefarah.gitbook.io/yq | docs |
| 24 | hashcat? no — netcat/hping only if needed | network debugging | — | — | — |
| 25 | Obsidian (free) | notes | — | obsidian.md | help.obsidian.md |
| 26 | Anki (free) | spaced repetition | — | apps.ankiweb.net | docs.ankiweb.net |

## Per-tool notes (common beginner mistakes + adoption)

1. **WSL2** — Mistake: installing tools inside Windows instead of WSL (every command you learn must be on Linux). Adoption: default for Windows devs.
2. **VS Code** — Mistake: not using Dev Containers; also learning vim vs VS Code debate is wasted time: learn vim survival mode + HATE no—practise; skip heavy vim configs.
3. **Git** — Mistake: committing secrets; force-pushing main. Adopt: trunk-based + short-lived branches.
4. **Bash** — Mistake: no `set -euo pipefail`; spaces in filenames handled wrong. Adoption: universal.
5. **Python** — Mistake: using system python without venv. Adoption: every tooling layer.
6. **Docker** — Mistake: fat images, running as root, no .dockerignore, pasting registry creds into Dockerfiles. Adoption: ~universal.
7. **Compose** — Mistake: not defining networks/volumes, no healthchecks. Adoption: default for local dev.
8. **GHCR** — Mistake: public images with private code. Adoption: default registry on GitHub shops.
9. **Actions** — Mistake: inline secrets, no OIDC, workflows too long (split into composite actions). Adoption: dominant among startups/mid.
10. **trivy** — Mistake: scanning only once at build (scan every deploy). Adoption: standard free scanner, also in CI templates.
11. **AWS free tier** — Mistake: not setting budget alarms on day 1; leaving instances running unused (the #1 "free tier bill" cause). Adoption: free tier is the industry's free lab — everyone's career starts here.
12. **localstack** — Mistake: expecting 100% AWS parity (it's 80%); use for CI tests only.
13. **Terraform** — Mistake: local-only state (lose it = rebuild everything); running apply without reviewing plan. Adoption: IaC standard. OpenTofu is the fully free drop-in fork — legal/backup knowledge worth having.
14. **checkov** — Mistake: never running it (run on every plan; fail builds on HIGH).
15. **Ansible** — Mistake: non-idempotent playbooks, secrets in files. Adoption: standard config-mgmt; YAML heavy.
16. **kind/minikube** — Mistake: using minikube for production-shaped things (fine locally); confusing kind's multi-node capability. Adoption: kind = CI default; minikube = local dev default.
17. **kubectl** — Mistake: `kubectl apply -f` in prod without GitOps, no aliases; forgetting `--previous` logs. Adoption: the daily driver.
18. **Helm** — Mistake: templating everything (fight complexity), not pinning chart versions. Adoption: standard packaging.
19. **ArgoCD/Flux** — Mistake: manual syncs in prod (destroys the GitOps value); ignoring `--insecure` red flags. Adoption: GitOps is the 2026 default.
20. **Prometheus/Grafana** — Mistake: dashboards without alerts; no recording rules; forgetting retention/cost. Adoption: free OSS standard (Datadog in big enterprise).
21. **OpenTelemetry** — Mistake: treating it as optional — it is headed to universal. Adoption: converging standard.
22. **Semgrep/gitleaks/ShellCheck** — Mistake: scanning only on release, not per-PR. Adoption: standard gates.
23. **jq/yq** — Mistake: parsing JSON with grep (every interviewer has a joke about this). Adoption: ubiquitous.
24. **Obsidian/Anki** — Mistake: collecting un-reviewed notes (notes ≠ memory). Adoption: career-long habit.

**Industry adoption scoreboard (2026 JDs):** CI/CD 67% · automation 58% · K8s 56% · AWS 54% · Python 53% · Terraform 50% · monitoring 47% · Docker 38% · GitLab 36% · Linux 31% · Grafana 25%+ · Ansible ~25%. Spend your hours in that order, not the reverse.
---

# Part 7 — Project Roadmap

Projects are the single most important investment in this roadmap — remember, only ~2% of DevOps postings are entry-level, so your projects ARE your experience section. Every project below must be: (1) deployed, (2) documented in a README with architecture diagram, (3) linked on LinkedIn/GitHub, (4) demo-able in 3 minutes.

## Level 1 — Beginner: Linux Homelab + Bash Automation Suite

- **Objective:** prove you can operate Linux and automate real tasks
- **Skills learned:** Linux ops, Bash, systemd, cron, SSH, shellcheck-grade reliability
- **Tech stack:** Oracle Cloud Always Free VM (or a laptop VM), Bash, systemd, cron
- **Features:** remote server; user management; automatic backups script with rotation; log reporter via webhook; scheduled health checks (disk, memory, service status) with alerts
- **Stretch goals:** add Ansible to reproduce the server config; add a second VM and sync
- **Deployment:** public IP + README proof screenshots; script output in the README
- **Time:** 1–2 weeks (parallel with Weeks 2–4)
- **Resume value:** low alone, but it builds Week 1–4 evidence — list under "Projects" once with the scripts
- **Interview discussion points:** idempotency, why cron over systemd timer (and vice versa), SSH hardening choices
- **README suggestions:** architecture diagram (simple), command reference table, "what surprised me" section, harden checklist
- **How to make it stand out:** include the painful bugs you hit (fixing them shows real experience); record the live demo

## Level 2 — Beginner/Intermediate: GitHub-Powered Deployment Lab

- **Objective:** first automated deploy; Git as the source of truth
- **Skills learned:** Git, GitHub Actions, deployment strategies (recreate), web servers
- **Tech stack:** static site (your portfolio later), GitHub Actions, free VM, nginx
- **Features:** commit → CI lints and builds → CD deploys to server; deploy notifications in commit status; rollback script
- **Stretch goals:** branch-environment mapping (dev staging / main prod); Slack/Discord webhook notification
- **Deployment:** the VM URL is the deliverable
- **Time:** 1 week (Week 9)
- **Resume value:** moderate — "automated CI/CD with 100% deploy success" line
- **Interview discussion points:** why static deploys first; failed-deploy recovery; artifact strategy
- **README suggestions:** workflow diagram, badge for build status, rollback proof
- **How to make it stand out:** demo a deliberate breaking commit → red pipeline → revert → green, recorded

## Level 3 — Intermediate: Dockerized 3-Tier Application

- **Objective:** containerize a real multi-service app with compose, then productionize the images
- **Skills learned:** Docker, Compose, networking, persistence, image security
- **Tech stack:** Docker, Compose, Flask (or Node) + PostgreSQL + Redis, nginx reverse proxy
- **Features:** 4–5 services; volumes for DB persistence; healthchecks; env-based config; non-root images under 200MB; trivy-clean images
- **Stretch goals:** add a worker queue (Redis/RQ) and graceful shutdown demo (SIGTERM handling)
- **Deployment:** compose on your VM; screenshot `docker compose ps` healthy
- **Time:** 2 weeks (Weeks 6–8)
- **Resume value:** high — containerization is on ~every JD
- **Interview discussion points:** multi-stage builds, layer caching, why healthchecks matter, graceful shutdown
- **README suggestions:** compose file walkthrough, network diagram, failure-mode table
- **How to make it stand out:** publish the images to GHCR publicly with tags — recruiters click and see real artifacts

## Level 4 — Intermediate: Full CI/CD Pipeline with Security Gates

- **Objective:** an end-to-end pipeline a hiring manager would recognize from their own company
- **Skills learned:** GitHub Actions, OIDC/MFA-free auth, security scanning, artifact management
- **Tech stack:** GitHub Actions, Semgrep, gitleaks, trivy, checkov, GHCR
- **Features:** PR checks (lint, unit tests) that must pass; merge → build → scan → push; deploy to VM; security gates fail the build; secrets via GitHub Environments, never in code
- **Stretch goals:** OIDC to AWS instead of static keys; matrix builds; caching speed optimization
- **Deployment:** live VM URL; pipeline status badge in README
- **Time:** 2 weeks (Weeks 9–10 + 23 hardening)
- **Resume value:** the #1 JD skill with visible proof
- **Interview discussion points:** explaining OIDC, why gates before merge, artifact immutability
- **README suggestions:** pipeline stages diagram, security matrix (scanner → what it catches), failure screenshots
- **How to make it stand out:** add a "security challenge" — include a test file with a planted secret that the pipeline catches; describe it in the README (shows DevSecOps thinking)

## Level 5 — Advanced: Terraform AWS Environment (Infra as Code)

- **Objective:** reproducible cloud environments, not console clicks
- **Skills learned:** Terraform, IAM, VPC design, state management, drift handling
- **Tech stack:** Terraform, AWS free tier (VPC, EC2, S3, RDS or DynamoDB, ALB), checkov
- **Features:** modules (network/compute/storage); remote state in S3 with DynamoDB locking; variables for envs (dev/staging/prod); tags everywhere; checkov-clean
- **Stretch goals:** `terraform import` real resources; add a GitHub Actions workflow that runs `terraform plan` on PR and `apply` on merge; OpenTofu compatibility note
- **Deployment:** environments you can destroy and rebuild in minutes (prove with CloudWatch-free evidence: CLI output screenshot)
- **Time:** 3 weeks (Weeks 15–16)
- **Resume value:** very high — IaC is a table-stakes skill
- **Interview discussion points:** why remote state, locking vs concurrent applies, what drift is and how you detect it
- **README suggestions:** state architecture diagram, module tree, plan output example, cost note ($0)
- **How to make it stand out:** the PR-driven plan/apply workflow — "infrastructure reviewed like code" — is a line that interviews will ask about

## Level 6 — Advanced: Kubernetes + GitOps (the Capstone)

- **Objective:** THE showcase project: production-shaped K8s with GitOps and observability
- **Skills learned:** Kubernetes, Helm, ArgoCD, GitOps, Prometheus/Grafana, networking, troubleshooting
- **Tech stack:** kind cluster (or managed-free tier where possible), Helm, ArgoCD, Prometheus, Grafana, ingress-nginx
- **Features:** your Flask app deployed exclusively via git commits → ArgoCD sync; Helm chart with env values; HPA; ingress with TLS (self-signed or free domain); Prometheus scraping + Grafana dashboards (requests, latency, errors, saturation); SLO + error budget alert; runbook directory; chaos exercise documented (kill pods/nodes → recovery notes)
- **Stretch goals:** add Loki log correlation; multi-env namespaces (dev/staging/prod); Velero backup drill
- **Deployment:** cluster runs on your laptop/VM — document access + demo scripts; record a 5-min video
- **Time:** 4–6 weeks (Weeks 18–22)
- **Resume value:** this is the project interviewers will ask about at every K8s role — make it your pinned repo
- **Interview discussion points:** desired vs observed state, GitOps failure modes, SLO math (error budget), how you debug a CrashLoopBackOff
- **README suggestions:** full architecture diagram, GitOps flow animation (ASCII or mermaid), runbook index, chaos test results table, dashboards screenshots, alert rules copy
- **How to make it stand out:** a "war story" section — one real incident you hit (e.g., etcd disk full, image pull backoff) and exactly how you diagnosed it

## Level 7 — Production Ready: Serverless Event Pipeline

- **Objective:** event-driven architecture + managed services fluency
- **Skills learned:** Lambda, API Gateway, DynamoDB, SQS, S3 events, DLQ patterns, IAM least privilege
- **Tech stack:** AWS free tier, Python boto3, CloudWatch
- **Features:** S3 upload → event → Lambda validates/fan-out to SQS → worker Lambda → writes DynamoDB + logs; DLQ captures failures; retries with backoff; cost $0/month proof
- **Stretch goals:** idempotent processing (dedupe on DynamoDB key), throttling demo, schema versioning
- **Deployment:** live S3 bucket + step-by-step demo in README
- **Time:** 2 weeks (Week 13)
- **Resume value:** high for platform/serverless roles — shows distributed-systems thinking (the mid↔senior differentiator)
- **Interview discussion points:** why DLQ, idempotency, retry vs redrive, event ordering
- **README suggestions:** event flow diagram, DLQ investigation runbook, cost analysis
- **How to make it stand out:** simulate a poison message and show the DLQ + investigation path end-to-end

## Level 8 — Startup-Level: Internal Developer Platform (IDP) Lite

- **Objective:** platform engineering — the fastest-growing specialization and the most realistic junior door
- **Skills learned:** platform thinking, self-service UX for engineers, CI template abstractions, docs
- **Tech stack:** GitHub repo templates, reusable workflows/composite actions, Scorecard/Backstage awareness (or templates + a docs portal via mkdocs — free)
- **Features:** a repo template + reusable workflows so a "developer" can bootstrap a new service with CI/CD, security gates, and deploy paths in minutes; an mkdocs portal documenting the platform; a demo "developer persona" walkthrough
- **Stretch goals:** add a second backend language template; automate granting access (app catalog); track self-service adoption metrics in the README
- **Deployment:** the portal site live; demo video (as the new developer) from zero to deployed in <10 minutes
- **Time:** 3–4 weeks post-capstone
- **Resume value:** extremely high signal for 2026 — platform engineering is THE growth area
- **Interview discussion points:** what "developer experience" means, golden paths, why self-service beats ticket queues
- **README suggestions:** persona stories, template usage statistics, golden-path diagram
- **How to make it stand out:** put your capstone app through your own platform — eat your own dog food as the demo

## Level 9 — Open Source-Level: Real CNCF/Ecosystem Contributions

- **Objective:** contribution graph + community credits recruiters actually recognize
- **Skills learned:** reading large codebases, PR etiquette, maintainer communication, CI on OSS
- **Targets (beginners welcome):** docs + typos in kubectl/helm/argocd/terraform-aws-modules; Prometheus/Grafana dashboards contributions; new "exporter" mini-projects; Chinese translations no — realistic first PRs: docs, tests, small bugfixes in any project on this list; add your own tools (a kubectl plugin, a trivy rule) to GitHub
- **Features:** a merged PR (start with docs!), a helpful issue reply, then a code PR
- **Stretch goals:** a merged non-docs PR; maintain a small tool with a real user; present at a local meetup
- **Time:** ongoing, weeks 20–24+ (1–2h/week)
- **Resume value:** high social proof; "merged PR in official ArgoCD docs" wins conversations
- **Interview discussion points:** how you navigated a big codebase, how you handled review feedback
- **README suggestions:** "My Contributions" section with links to merged PRs
- **How to make it stand out:** quality over quantity — one well-done contribution beats ten typos
---

# Part 8 — GitHub Portfolio Plan

Your GitHub is your resume, portfolio, and living proof of every skill claim. Recruiters open it before your PDF.

## Repository structure

- **org or personal branding:** use one consistent name across GitHub, LinkedIn, and your site
- **One skill = one repository** — never one mega-repo with everything (recruiters can't navigate it):
  - `devops-labs` (Weeks 1–4 exercises as organized scripts)
  - `ci-pipeline-unified` (Level 4 pipeline project)
  - `terraform-aws-environments` (Level 5)
  - `kubernetes-gitops-capstone` (Level 6 — your flagship)
  - `serverless-event-pipeline` (Level 7)
  - `internal-developer-platform` (Level 8)
  - `portfolio-site` (Level 2 + your site)
- **Directory discipline:** every repo gets `README.md`, `docs/`, `screenshots/` or `diagrams/`, `.github/workflows/` where applicable, `.gitignore`, `LICENSE` (MIT)

## Pinned repositories (max 6)

Pin these in order: capstone (K8s+GitOps), Terraform envs, CI pipeline, serverless pipeline, IDP, portfolio site. Pins should take a stranger from zero → "yes, this person can do the job" in about 20 minutes of reading.

## README formula (every project)

1. One-paragraph problem + your solution (plain language, no jargon first)
2. Architecture diagram (mermaid or draw.io export — mermaid renders on GitHub natively)
3. Tech stack badges (shields.io) + live status badge (CI passing, uptime)
4. Quickstart: exact commands a stranger can run to see it
5. "Failure/learnings" section — the bugs you hit and how you fixed them (this is where juniors win)
6. Screenshots of the live system (dashboards, pipeline runs, terminal)
7. Demo video link (5 minutes max — free hosting: your repo's README can embed a YouTube unlisted video)
8. Roadmap of what you'd add next (shows you think in iterations)

## Portfolio website

- **Build it with your own pipeline** (GitHub Pages + Actions): it doubles as a project (Level 2) and hosts your resume, projects, blog
- Use a free template (e.g., Hugo/astro on GitHub Pages or plain HTML+CSS — no money needed)
- Structure: hero (who you are + headline), skills matrix (with proof links), projects (same order as pins), resume download, contact
- Add a blog: 4–6 posts during the 6 months ("How I built a GitOps cluster on my laptop", "Debugging my first CrashLoopBackOff") — recruiters and interviewers WILL read these, and they reteach you the material (Feynman technique)

## Contribution graph strategy

- **Commit daily from Week 3 onward, even 1 line of docs** — the streak is social proof of the "consistent daily study" claim
- Commit meaningful chunks: notes, script iterations, docs, project code
- Never fake contribution counts (recruiters dig and it destroys trust); an honest streak with real repos beats a padded one

## Commit frequency & message quality

- 1–5 commits/day on study days; conventional commits style (feat:, fix:, docs:, chore:)
- Each commit = one logical unit with a message a stranger understands
- PRs to yourself from branches (exercise the review muscle on your own repos)

## Open-source contributions

- Weeks 20+ : 1–2h/week toward docs/testing/bugfix PRs (see Level 9)
- Start with a small project you actually use (your tools: kubectl aliases collection, trivy rule, Helm chart, a Prometheus exporter for a hobby service)
- Contributing to CNCF ecosystem shows: you can read other people's code, follow maintainer processes, and communicate — three interview skills

## GitHub profile optimization

- Profile README (pinned): who you are, what you're building toward, skills with real links, current focus ("building GitOps clusters and open-source infrastructure")
- Bio: role-targeted — "DevOps Engineer candidate — CI/CD, Kubernetes, Terraform, AWS" (searchable keywords)
- Avatar + banner consistent with LinkedIn
- Stars/following/orgs: follow the Kubernetes, CNCF, HashiCorp, Grafana orgs (shows where you live)
- Achievements: earn the Pull Shark and YOLO badges naturally via open-source work

## Best practices recruiters actually notice

1. Live links (deployment URLs) in every README — clicking through beats reading
2. CI badges that are green (nothing signals "junior who stops" like dead red badges)
3. Architecture diagrams (less than 5% of candidates have them)
4. A "war story"/incidents section (rare, memorable, honest)
5. Consistent documentation voice — READMEs people can actually follow (rare in juniors)
6. No leftover secrets anywhere (scan with gitleaks before you share)
7. One flaw-proof demo video for the capstone (script it, record twice)

---

# Part 9 — Resume Roadmap

## Resume structure (one page until you have 5+ years; two only with real SAAS-scale work)

1. **Header:** Name, location, email, phone, LinkedIn URL, GitHub URL, portfolio URL — all clickable
2. **Headline:** "DevOps Engineer | CI/CD · Kubernetes · Terraform · AWS" (mirrors the role title exactly — ATS matching)
3. **Summary (2 lines):** "DevOps-focused engineer building CI/CD pipelines, containerized workloads, and IaC on AWS. Portfolio: [link]. Open to entry/junior DevOps, Platform, or SRE roles."
4. **Key skills (tools first):** CI/CD (GitHub Actions, GitLab CI) · Docker · Kubernetes · Helm · Terraform · AWS (VPC, EC2, S3, IAM, Lambda) · Bash · Python · Prometheus/Grafana · Ansible · Linux · Git
5. **Projects (your experience section):** 3 entries, each with: name, result-oriented line ("Cut deploy time from 30 min manual to 4 min automated"), tech stack line, 2 bullet achievements with metrics, link (checkmark if live)
6. **Experience (if you have any, any field):** even non-tech work goes here with transferable lines ("managed X, reduced cost Y, led Z people") — never leave it blank; if truly none, replace with "Certifications" + "Volunteer/Community" (e.g., a local meetup you run)
7. **Certifications:** only earned ones with links; "in progress" never on the resume (mention in interviews instead)
8. **Education (if any):** one line, only if recent — skills beat degrees in 53%+ of postings

## ATS optimization

- Use a single-column, text-friendly layout (no tables, graphics, or icons — ATS chokes)
- Standard section titles: Summary, Skills, Projects, Experience, Education, Certifications
- Include exact keywords from the JD — this is why you write a fresh resume per application (Part 13)
- Save as PDF named `Firstname-Lastname-DevOps-Engineer.pdf`; no candidate IDs or dates in filename
- Test with free ATS checkers (Jobscan free tier; skillsyncer.com free tier)

## Skills section rules

- Group as: "Core: Linux, Git, Docker, Kubernetes, Terraform, AWS, CI/CD, Bash" / "Also: Python, Ansible, Helm, ArgoCD, Prometheus, Grafana"
- Only list what you can defend in a 10-minute follow-up question

## Projects section rules (your real experience)

- Format: `ProjectName — link` | stack line | 2–3 bullets with numbers ("self-healing demo: recovered in 4s"), outcome claims only if reproducible (a stranger can run the Quickstart)
- Capstone first; then Terraform project; then CI/CD pipeline

## Experience section when you have none

- Replace with: "Open Source & Community" (merged PRs, meetups attended, workshops you've run for peers), "Continuous Learning" (6-month curriculum with links — shows the discipline hiring managers love)
- You are NEVER blank: the projects section IS the experience

## Achievements

- Numbers only: response times, deploy times, uptime, cost ($0 free tier), lines of IaC, days of streak, users of your dev platform

## Common resume mistakes

1. Claiming skills without live proof (every claim = a repo link)
2. Generic summary ("highly motivated team player") — replace with quantified specificity
3. Listing "AWS" but having no AWS artifacts
4. Typos in commands/tool names (kubrenetes, chmod/CHMOD) — instant credibility kill
5. Applying the same resume to all roles (keyword-less)
6. Length >1 page for a 6-month journey
7. No portfolio link or broken links

## Resume keywords to include (2026)

CI/CD · GitHub Actions · GitLab CI · Docker · Kubernetes (K8s) · Helm · ArgoCD · Terraform · Infrastructure as Code · AWS (EC2, VPC, S3, IAM, Lambda, CloudWatch) · Linux · Bash · Python · Ansible · Prometheus · Grafana · OpenTelemetry · Observability · Monitoring · Alerting · DevSecOps · Security scanning (trivy, checkov, Semgrep) · GitOps · Automation · Incident response · SLO/SLI · Problem solving · On-call · Self-healing · Autoscaling · Cost optimization · Platform engineering

## Tailoring for this specific role

- Read the JD → map each requirement to one of your projects/labs/skills (requirements that don't exist in your profile get a "learning in progress" note in interviews, never on paper)
- For DevSecOps roles: lead with security projects; for Platform roles: lead with IDP + GitOps; for SRE roles: lead with SLO/observability work; for generalist: the balanced layout above

---

# Part 10 — LinkedIn Optimization

## Headline (top line under your name)

- Formula: `[Target title] | [3 core skills] | [what you ship]`
- Example: "DevOps Engineer | Kubernetes · Terraform · AWS | Building GitOps pipelines and observable infrastructure"
- Include 2–3 search keywords recruiters grep for; drop "aspiring" — you ARE the engineer you're building toward.

## About section

- 3 short paragraphs: (1) what you do + what you're building now, (2) proof — projects with links and numbers, (3) what you're looking for (entry DevOps/Platform/SRE, remote, freelance) + call to action (message me)
- First 2 lines must hook (they're the preview text) — start with the war story, not "passionate about technology"
- Link every project; add your portfolio URL

## Banner

- Clean, personal: a banner image with your name + one-line positioning + URLs (free: Canva). No stock-photo clichés.

## Featured section

- Pin 4–5 items: portfolio website, capstone repo, capstone demo video, best LinkedIn post, resume PDF

## Projects (LinkedIn Projects section, not just Featured)

- Add each repo as a Project: name, URL, 2-line description, skills tagged. Repeat keyword structure from resume (ATS + LinkedIn search both index this).

## Posts (weekly content plan)

- Week 1–2: post once — "Day 1 of building a GitOps cluster" (screenshots + lesson)
- Then 2–3 posts/week, rotating: (a) build logs ("Today I fixed X by Y — here's the exact command"), (b) teach-backs ("What a CrashLoopBackOff actually means, in plain words"), (c) project reveals (with demo videos), (d) one industry takeaway ("Why every CI pipeline needs gitleaks")
- Engagement rules: reply to every comment in 24h; comment on 10 industry posts/day (thoughtful, not "great post!")
- Posting IS practice — each post forces you to explain the material (interview prep on autopilot)

## Networking strategy

- Connect with: 20 recruiters (title contains "DevOps/Cloud/SRE" + "Recruiter/Talent"), 15 DevOps engineers at target companies, 5 hiring managers, 3 local meetup groups
- Personalize connection notes (2 lines: who you are + one specific thing about them/their company)
- Join: DevOps & Platform Engineering groups (HashiCorp, CNCF communities) — engage, don't lurk

## Cold outreach (the highest-ROI action in this roadmap)

- Template for engineers: "Hi [Name], I'm a DevOps engineer candidate building [specific project]. I saw you work on [X] at [Co] — I'd love 10 minutes to ask how your team handles [specific topic]. Happy to share my repo first."
- Template for recruiters: "Hi [Name], I'm a DevOps candidate with a portfolio showing [K8s+GitOps capstone, Terraform AWS envs, CI/CD security gates]. Could you flag me for entry DevOps/Platform roles?"
- Send 3–5/day, track replies, follow up once after 5 days (polite single follow-up is professional, not annoying)

## Recruiter visibility

- Set "Open to Work" (visible to recruiters only, or public during final month)
- Let recruiters find "the thing": your headline keywords + Featured projects do the selling; a warm intro beats 100 cold applications
- Post frequency + engagement score: recruiters message candidates who post about their stack

## Weekly review habit

- Sunday: respond to all outreach, publish 1 post, add 10 new connections, note which projects to mention in next posts
---

# Part 11 — Interview Preparation

## Interview flow for DevOps roles (2026)

1. Phone screen (recruiter): motivation, availability, salary expectations, portfolio sanity check
2. Technical screen (1h, usually live coding or scenario questions): Linux/network/CI-CD/Git
3. Onsite/technical loop (2–4 rounds): live troubleshooting scenario, system design, behavioral, sometimes a take-home
4. Hiring manager round: culture, teamwork, on-call attitude

## Technical interviews

**Live troubleshooting is the DevOps interview signature.** Two drills cover most cases:

- **Drill A — Diagnose this system:** "Your pipeline fails at the deploy step / a pod is CrashLoopBackOff / the site is slow." Practice the *method*, not the answer: (1) define the symptom, (2) gather data (logs, metrics, status), (3) isolate the layer (code? dependencies? infra? network?), (4) reproduce, (5) fix + verify, (6) prevent recurrence.
- **Drill B — Explain this config:** be able to read any YAML/Dockerfile/Terraform on screen and narrate it (probes, limits, healthchecks, state). Practice by reading your own projects 10 times out loud.

**The 20 questions you must answer cold (no notes):**

1. Container vs VM vs bare metal — what's actually different?
2. What happens when you run `docker build` on a Dockerfile (layers, cache)?
3. How does docker-compose connect services (networks, DNS)?
4. Explain a GitHub Actions workflow: triggers → jobs → steps → artifacts.
5. What's the difference between CI and CD? Give a concrete CD example.
6. Green/blue vs canary vs rolling deployment — compare + when to use each.
7. What is Terraform state, and why must it be locked and stored remotely?
8. Plan/apply vs apply — why is `terraform plan` the most important command?
9. Terraform vs Ansible — where does each belong?
10. Kubernetes architecture in 60 seconds (control plane vs nodes and what each runs).
11. What's a pod vs a deployment vs a service? How do you expose a workload?
12. Liveness vs readiness vs startup probes — and why a wrong probe takes down apps.
13. How does a service discover another service in K8s (DNS)?
14. What is a crash loop, and what are the top 5 causes + how you diagnose.
15. Requests vs limits — what happens when a pod exceeds them.
16. Prometheus scraping model + what a metric/alert do; PromQL rate() example.
17. SLO, SLI, error budget — define them and give one example of each.
18. How do you store secrets properly (env vs Vault vs K8s secrets vs SSM)?
19. How would you secure a CI/CD pipeline end to end (5 concrete controls)?
20. A service is slow in prod at 3pm. Walk me through your runbook.

**Plus the classic "explain to a non-technical person":** "What do you actually do all day?" — have a 90-second answer.

## HR interviews

- "Tell me about yourself" → 90 seconds: now (what you're building), before (what you did), why this role/company (2 researched specifics)
- Salary question: give a researched range for your market + "open, based on role scope and location"
- "Why should we hire you with no experience?" → "my portfolio is my experience" + name 3 proof points
- "Why do you want DevOps?" → honest, specific (automation + systems + reliability), avoid "I love YAML"
- Know the company: 3 facts from its About page + 1 from its tech blog; one question for them about their stack

## Behavioral interviews (STAR, always with numbers)

Prepare 6 stories from your build journey, each with a failure and a fix:

1. A project that broke and how you debugged it (capstone incident)
2. When you were stuck on something for 2+ days and how you got unstuck
3. A time you disagreed with a recommendation/what someone said (about your approach)
4. A time you automated something boring (which script, who it helped)
5. A time you had to explain something technical to a non-technical person (blog post!)
6. A time you faced an on-call-style emergency and stayed calm (chaos day!)

## Problem-solving rounds

- Linux: OverTheWire + HackerRank shell drills (already in your plan — they ARE the interview)
- Coding: 1–2 easy + 1 medium Python problems/week (know strings, dicts, lists, two-pointer basics)
- Log analysis: parse a log, count patterns, find the error trace — practice with awk/sed/jq on real logs
- Config reading: your own repos are the practice set

## System design (junior-friendly version)

Most entry DevOps design prompts are "design a CI/CD system / deploy a web app / set up monitoring." Use this 5-minute framework: requirements → components (app, DB, cache, CDN if any) → infra (VMs vs containers vs serverless — justify) → CI/CD flow → security (secrets, least privilege) → observability (metrics, alerts) → failure modes + rollback. Learn 3 patterns by heart and whiteboard them: 3-tier on cloud, GitOps deployment pipeline, event-driven pipeline. Resource: ByteByteGo newsletter/blog free tier (blog.bytebytego.com).

## Portfolio walkthrough & project explanation

- Script a 3-minute capstone demo (K8s + GitOps): problem → architecture → demo (live or video) → one failure + fix → what you'd do next
- Prepare for "what was the hardest bug?" — one story with exact commands you ran (your README war stories are this)
- You WILL be asked "did AI write this?" — answer honestly: "I used AI to accelerate, here's what I changed and why; here's the architecture decision I made that it didn't make for me"

## Mock interview strategy

- Pramp (pramp.com): free peer mock interviews (schedule consistently, 2×/week from Week 20)
- AI practice: ChatGPT/Claude can role-play interviewer (Part 17) — record yourself answering; replay for filler words and rambling
- Self-mock every Sunday: 10 questions from the list above, out loud, timed
- Get real reps: apply and interview even before you feel ready — interviews are practice too (but know the 20 questions first)

## Whiteboard strategy

- Ask for scope before writing ("is this a small app or a 500k-user deployment?")
- Name the pieces first, then draw, then narrate trade-offs (they want your process, not pixels)
- Say "I'd check X" instead of guessing; for unknowns: "in my lab I'd test this by Y"
- Never hand-wave security or cost — two words interviewers zero in on

## Communication tips

- Answers under 90 seconds; then stop.
- If you don't know: "I don't know for sure — here's how I'd find out" (DevOps loves honest debugging, hates bluffing)
- Define acronyms once; match the interviewer's depth
- Tell stories with structure: setup → problem → action → result

---

# Part 12 — Coding Practice Plan

DevOps interviews are ~30% code, ~70% systems. Budget 45–60 minutes/day; never sacrifice projects for it.

## LeetCode roadmap (Python)

- Weeks 1–5: Easy warm-ups — Arrays & strings (contains-duplicate, valid-palindrome, two-sum, valid-parentheses, best-time-to-buy-sell)
- Weeks 6–10: Easy/medium — hashmaps, sliding window basics (longest substring, max subarray), linked lists basics
- Weeks 11–16: Medium focus — trees (BST basics), two pointers, intervals
- Weeks 17–24: Keep 1–2 medium/week only; switch to system-design and config-reading time
- Target: 40–60 problems total, mostly easy with ~10 medium. DevOps interviews rarely go beyond this.

## HackerRank roadmap

- **Linux Shell track (mandatory):** all 53 problems — this IS the DevOps interview pattern (sed, awk, grep, bash scripts). Do Weeks 4–6.

## Codeforces / CodeChef (only if interviewing at product companies with hard DSA)

- Not required for DevOps; do Codeforces problems 800–1100 (the "A" level) as optional warm-ups if you have extra time. Skip entirely otherwise.

## Exercism

- Python track: 25+ exercises (mentored, free). Bash track: 20 (strings, control flow).
- Weeks 4–8; after that, sporadic (it's a review tool, not a daily drive)

## Frontend Mentor / Project Euler

- Frontend Mentor: skip (that's for frontend).
- Project Euler: optional for Python problem-solving joy — problems 1–25 are good warm-ups; never your daily driver.

## Daily practice schedule (45 min)

1. **10 min:** 2 problem-easy or a HackerRank shell problem
2. **15 min:** 1 LeetCode (escalating difficulty per the roadmap)
3. **20 min:** system-config reading or log parsing (awk/sed/jq drills on test logs) — the forgotten interview skill

## Difficulty progression

- Month 1: easy only + shell track. Month 2: easy + 1 medium. Month 3: medium focus. Month 4–6: medium with stopwatch (10-min max on unknown, read the solution, re-solve tomorrow — spaced repetition beats grinding)

---

# Part 13 — Job Search Strategy

## When to start applying

- **Soft launch: Week 12.** Apply to 3–5 internships/apprenticeships/week while still learning (the interview practice is free; you're expected to be mid-education)
- **Real launch: Week 20–22.** Portfolio at capstone stage, resume + LinkedIn live, 20 interview answers cold — start 10/day
- **Full throttle: Week 24.** All systems go until an offer lands (Part 19 gives the daily cadence)

## How many applications per day

- 10 quality applications/day beats 50 spam ones. Quality = tailored resume + personalized note (when possible) + correct keywords. Measure: interviews ÷ applications; aim for 5–10% interview rate for entry roles (realistic for this market).

## Where to apply (in priority order)

1. **Direct company pages** (highest conversion): hunt "Platform Engineer", "DevOps Engineer", "Site Reliability Engineer", "Cloud Engineer", "Backend DevOps" (+ "Intern", "Associate", "Junior", "Entry") on target companies you follow on LinkedIn
2. **LinkedIn Jobs** (filter: Entry level, Remote, Date-posted <7 days — apply fast, early applicants win)
3. **DevOps-specific boards:** devjobs.pro (DevOps/cloud filtered); CNCF job board (jobs.cncf.io); SysAdmin/DevOps niche boards (dice.com for US)
4. **Remote boards:** remoteok.com; weworkremotely.com; remotive.com; travail? no. Arc.dev
5. **Startup boards:** wellfound.com (startup DevOps gigs, direct founder chats)
6. **Internship:** internships portals — LinkedIn, Wellfound, Google internships (google.com/careers — check open engineering internships), Microsoft IoT? no — check each target company's careers page for "intern" postings; also "Graduate DevOps Engineer" programs
7. **Jobs-to-curate:** "Cloud Support Associate", "Associate Site Reliability Engineer", "Backend Engineer (ops-leaning)", "Technical Support Engineer" at infra companies — 3–6 months in these rolls INTO DevOps and some convert to internal DevOps teams. These are the real junior entry points (see the 2% stat).

## How to track applications

Notion/Excel sheet with columns: Date | Company | Role | Source | Resume version | Outreach contact | Status (Sent/Viewed/Replied/Interview 1/2/3/Offer/Reject) | Follow-up date. Review weekly: what's converting, what's not, adjust keywords.

## Cold emailing (with referral flavor)

- Find the hiring manager or a senior engineer (LinkedIn) → 5-line email: who you are, one line about their stack (prove you read), one line about your matching project (live link), ask: "Would you consider an entry/platform role candidate with this portfolio?" — attach nothing, everything is linked
- 3–5/day; reply rates double when you reference something specific from their GitHub/tech blog

## Referral strategy

- Every connection you make is a referral network. Ask: "Would you feel comfortable referring me to the DevOps/Platform opening at [company]?" (LinkedIn referral button makes it 10 seconds)
- Give them material to forward: your 90-second story + portfolio link
- Referrals spike interview rates from ~3% to ~30%+ — it's the biggest multiplier you control

## Recruiter outreach

- Reply to every recruiter message; ask every recruiter (even for wrong-fit roles): "Who else do you know hiring entry cloud/platform engineers?" — recruiters move candidates around
- Agency recruiters (Volt, TEKsystems, etc.) are free job engines for US entry roles — send your portfolio

## Expected timeline (realistic)

- Weeks 12–20 (soft): a few interviews; treat as practice + feedback loops
- Weeks 20–24 (hard): 40–150 applications; expect 3–8 interview loops total for entry
- Weeks 24–32: 1–3 offers typical for the top-decile portfolio this roadmap builds; everything usually resolves within ~6–8 weeks of full-throttle applying
- If a cycle stalls: revise portfolio ranking, get 3 resume reviews (reddit r/resumes, r/devops friendly threads), and add ONE adjacent role type (support/backend-ops) to the funnel
---

# Part 14 — Freelancing Roadmap

Freelancing is the fastest way to convert the roadmap into income AND into a line on the resume ("Client: set up CI/CD for a 30-person startup"). Do this in parallel from Week 10 onward, 2–5h/week.

## Services you can genuinely sell as a 6-month learner

- **CI/CD setup** — "I'll wire GitHub Actions so your team auto-tests and auto-deploys" ($200–$800/setup)
- **Dockerization** — 'containerize your legacy app so it runs anywhere' ($150–$700)
- **Monitoring/dashboard install** — Prometheus + Grafana dashboards and alerts ($200–$600)
- **Terraform migration** — 'recreate your console-clicked infra as code' ($300–$1,000)
- **Server hardening / security checklist** — SSH, fail2ban, least-privilege ($100–$400)
- **Deploy/DevOps audits for startups** — a 2-page report with 5 fixes ($150–$500)
- **Personal dev-environment setups** — WSL, containers, dev containers for small teams ($50–$200)

Start with the services you've *done in your own lab* — every project in Part 7 is a breadcrumb into a service.

## Get your first client

1. **Where clients find you:** Upwork (category: DevOps / CI-CD), Contra (flat-salary platform), Fiverr (smaller projects), LinkedIn "offering services" announcement post, and — highest conversion — your network: tell every tech-adjacent person you know "I now set up CI/CD and deploys for small teams, $300 flat"
2. **First contract psychology:** price the FIRST job 30% below market to win it fast and ask for a testimonial + permission to use it; nobody knows your portfolio yet, so the price IS the marketing
3. **Nail one reference:** one happy startup founder's recommendation unlocks the next five clients

## Build trust

- Deliverables: README-style handoff docs (runbooks), graceful demos, before/after screenshots
- Work on a staging/replica first, never on prod without explicit scope; write down acceptance criteria from day 1
- Over-communicate: update client weekly even when there's nothing to show ("here's the plan for next week")

## Pricing without experience

- Hourly: $25–$50 entry (market benchmark; adjust to your location's cost of living), or flat rates above for defined-scope work (flat is safer for you — you'll get faster)
- Never price by "how long it will take me twice as long as I think" — price by value delivered + competitor rates, then eat the learning cost on your own time

## Proposal writing (the 5-part formula)

1. "I read your job post / talked to [name] — here's the problem I can solve" (echo their words)
2. Your exact approach in 3 bullets (tools you'll use, what they'll receive)
3. Past evidence: your most similar project link + one sentence on it
4. Timeline + fixed price + communication schedule
5. One question about their stack (shows depth; filters bad-fit clients)

## Client communication

- Ask questions BEFORE starting (deploy target, access, expectations, success criteria) — this one habit filters out 80% of failure cases
- Write everything down: scope, timeline, price, what's out of scope (email recap = contract)
- Status updates weekly; demo videos for everything visual
- Say no to impossible timelines; promise small, ship early, over-deliver late

## Delivery

- Deliver on staging + give a runbook; don't just "make it work" — leave them able to run it (that's what separates you from a script-kiddie hire)
- Keep a handoff checklist: docs, credentials rotation notice, backup, rollback plan, 30-day support window

## Upselling

- After a clean delivery: "I noticed you're also running [X] manually — I can automate it for $Y" (one relevant offer, not a menu)
- Each project's carry-ons: monitoring → alerting → CI gate for security → IaC for the whole env
- Convert freelancers-turned-trusted → monthly retainer: "one maintenance + improvement hour/week"

## Platforms (for + against)

- **Upwork:** biggest volume; takes ~10 proposals before first win; optimize profile for "DevOps" keywords; ignore "test task" scams
- **Contra:** flat-fee, portfolio-first profile; good for showcasing projects
- **Fiverr:** you are a product page; small scope first (gig: "deploy your app with GitHub Actions")
- **LinkedIn + local meetups:** zero-competition grapevine — best for your first 2 clients
- **Local businesses/startup communities:** agencies, small SaaS, digital agencies that need infra but don't hire ops — pitch light infomercials

## Avoid scams

- Never pay to register/apply; never accept "overpayment" checks; never do "the job before the contract" for strangers; never grant prod access before written scope; prefer milestone payments (50/50) on first contracts; treat "urgent, one hour" requests as red flags; Upwork-based clients are vetted — prefer new-client work there while building trust

---

# Part 15 — Common Mistakes

1. **Tutorial hell** — watching 200 hours, typing 20. Fix: the 60/40 rule — 60% build, 40% consume; no project, no video.
2. **Skipping Linux/Git** — the two skills you use all day, every day, forever. Fix: Weeks 1–3 are non-negotiable.
3. **Console-clicking instead of coding infra** — you learn the UI, not the trade; interviews test the trade. Fix: every cloud action via CLI or Terraform.
4. **Tool-hopping** — "should I learn Jenkins or ArgoCD or Ansible…" Fix: finish the roadmap order; the roadmap IS the answer to tool choice.
5. **YAML without understanding** — copy-pasting configs then panicking when the follow-up question arrives. Fix: read the docs behind every config you paste; narrate it out loud.
6. **Deploying nothing** — the "$50/yr VM-less" portfolio. Fix: from Week 2 onward something is always live.
7. **Ignoring security** — insecure images/secrets. Fix: trivy/gitleaks from Week 8; security is a feature.
8. **Skipping documentation** — runbooks, READMEs, blog posts. Fix: docs are deliverables; version them in Git.
9. **Not tracking costs on the free tier** — the classic "free tier became $40" shock. Fix: billing alarm day 1; destroy before weekends; note $0 proofs.
10. **Grinding LeetCode instead of systems** — DevOps interviews test troubleshooting; fix: follow Part 12's ratio.
11. **Burnout pacing** — 10 hours/day for 3 days, then 2 weeks off. Fix: 4–6h/day, Sundays off, the productivity system in Part 16.
12. **Applying before portfolio maturity** — sending a resume that looks like 50 other beginners. Fix: only apply soft-launch until Week 20.
13. **Generic resume/LinkedIn** — no keywords, no links. Fix: Parts 9–10 are checklists, not advice.
14. **Isolation** — learning alone with zero community. Fix: CNCF Slack, r/devops, one Discord — be *seen*.
15. **Ignoring the 30–50% communication quota** — "it's a people job with YAML." Fix: blog + teach-backs from Week 6 (Part 10's posting plan).
16. **Refusing adjacent roles** — "I must be titled DevOps Engineer or nothing." Fix: support/platform/backend-ops roles convert within 6–12 months (that's how most people actually enter this market).

---

# Part 16 — Productivity System

## Daily routine (4–6h block, split sessions)

- **Session 1 (90 min, morning):** hardest topic first (learning) — after breakfast, no phone
- **Break (15 min):** walk, water, no scrolling
- **Session 2 (90 min):** building (project/lab)
- **Lunch + rest**
- **Session 3 (60 min):** practice (Bash/Python drills, LeetCode)
- **Session 4 (30–60 min):** notes, docs, README, daily git commit, one LinkedIn post draft
- Fixed start time daily (e.g., 8:00) — consistency beats intensity

## Weekly routine

- Mon–Fri: 4–6h/day as above
- Sat: project marathon + chaos day (break things deliberately) + social (one community chat)
- Sun: full review — revision quiz, weekly milestone check (from Part 3), plan next week, ONE zero-work hour outside (sports/walk); light reading only

## Revision strategy (spaced repetition)

- Anki (free): make 5–10 cards/day of commands + concepts (K8s architecture, Terraform state, PromQL snippets); review train daily (target: 30 cards/day, ~10 min)
- Weekly "from memory" exercises: whiteboard the cluster architecture, write the 20 interview questions' answers every Sunday
- Every month: re-build one project without looking (the gold standard — if you can't, you haven't learned it)

## Note-taking system

- Obsidian vault (free, local) in the same structure as the roadmap: `01-linux/ 02-git/ ... 10-observability/ 99-interviews/`
- Every note: what/why/how + one command example + one question to ask an interviewer
- Link notes to projects ("capstone #kubernetes") — Obsidian graph becomes your revision map
- Never collect un-reviewed notes: monthly cleanup; delete or merge anything not reviewed

## Project schedule

- One active project track + one maintenance track (portfolio/README updates) + the weekly mini-project in Part 3. Never 3 active builds at once.
- Projects get explicit finish criteria (checklist from Part 7) — "done" beats "perfect"

## Burnout prevention

- The 80% rule: on bad days, 80% effort still moves the mountain (2 hours > zero)
- Scheduled zero-days: one full Sunday off monthly
- Watch the warning signs: skipping Anki, dreading the computer, no commits — those are "slow down and re-plan" signals
- Celebrate milestones visibly: each Capstone-Part checkmark gets a LinkedIn post (that doubles as marketing)

## Deep work schedule

- Deep work = learning + building blocks (3h/day). Shallow = notes, posts, emails (1h)
- Phone in another room during deep blocks; single tab discipline — one doc + one editor + one terminal
- Use a focus app (free: "Cold Turkey" / "Forest" free tier) if attention drifts
- Block scheduling: your calendar IS the plan (calendar the daily blocks for the next 7 days on Sunday)

## Progress tracking

- The daily git commit IS the tracker (streak = progress)
- Notion/Excel: weekly table — hours studied, lessons completed, mini-projects finished, Anki cards reviewed, LeetCode count, applications sent
- Monthly self-review against Part 20's checklist — every month you should tick off a new section
- Keep a "before/after" file: paste the first script you wrote vs this week's (morale fuel + interview proof)

---

# Part 17 — AI Tools

## The free stack that earns its keep

- **ChatGPT free / Claude free / Gemini free** — debugging partner, concept explainer, config reviewer, mock interviewer; rotate between them (each has different blind spots)
- **GitHub Copilot free tier (VS Code)** — inline completions for Python/Bash/YAML boilerplate
- **Ollama + Continue.dev (fully free, local, private)** — run a local model for drafts/review without sending anything to the cloud; great for interview scenario Q&A
- **Claude (projects) / NotebookLM (free)** — paste docs (Kubernetes docs, Terraform docs, your notes) and interrogate them; NotebookLM also generates review quizzes from your sources
- **DeepSeek/R1 free web** — long-form reasoning for architecture questions (good for system-design practice prompts)
- **youtube transcript → summary (free via transcript tools or NotebookLM)** — turn 4-hour courses into 15-minute revision notes (always rewatch the hands-on parts; summaries can lie)

## When to use them

1. **Explain errors:** paste a traceback/log; ask "what's the most likely cause + how do I confirm?" — then verify
2. **Review my config:** "review this Dockerfile/K8s manifest — what would a senior change?" — then apply changes deliberately
3. **Generate the boring 80%:** boilerplate YAML skeletons, sed/awk one-liners to study, regexes, GitHub Actions scaffolding
4. **Mock interviewer roleplay:** "interview me as a senior DevOps engineer — 10 questions, grade at the end"
5. **Rewrite my docs/README/cover notes** (always edit before publishing)
6. **Turn logs into insight:** paste your capstone's incident logs; ask for a hypothesis list to test

## When NOT to use them

- **Never for the first build:** your first Dockerfile, first Terraform module, first chart must be 100% yours — otherwise the interview follow-up exposes the gap
- **Never during diagnosis drills:** do Drill A (Part 11) blind, then check with AI
- **Never copy-paste into projects without understanding:** every pasted block gets a comment-free mental review: "could I rewrite this from scratch?"
- **Never for interview answers you "learned" from AI without testing them** — AI invents commands (hallucination is real in 2026 too); verify everything against docs
- **Never for writing scripts that touch real data without reading them fully**

## How recruiters view AI-assisted work

- Normal and expected: 85–90% of engineers use AI daily (DORA/JetBrains surveys); asking candidates to solve problems with AI during interviews is increasingly the *norm*
- What converts "used AI" into "impressive": you can (1) explain what it generated and why it's correct, (2) show where you deviated from its output, (3) cite the change you made for security/reliability reasons it missed
- What kills you: claiming work you can't explain ("I asked ChatGPT"), or using AI to fabricate project history
- Interview answers that land: "Copilot wrote the skeleton; I rewrote the Dockerfile for non-root + multi-stage after reviewing the docs myself; the incident was mine to debug"

---

# Part 18 — Industry Roadmap (After Landing the First Job)

## Junior → Mid-Level (Years 1–2)

- Goal: own a service end-to-end — pipeline, deploy, monitor, on-call, runbook
- Learn at work: incident reviews (write them), runbook quality, cost monitoring, feature-flag rollouts, your company's real architecture
- Pick up: deeper PromQL, K8s upgrades, Helm chart authoring, Terraform modules in anger, bash/Python at "senior aide" level, one cloud cert (funded)
- Contribute: docs-in-repo culture, dashboards that people actually use, alert noise reduction (huge visible win)

## Mid-Level → Senior (Years 2–4)

- Specialize: Platform Engineer (IDP/templates/Golden paths) OR SRE (SLOs, error budgets, capacity planning) OR DevSecOps (security gates, policy-as-code)
- Learn: Go (operators/CLIs), service mesh, multi-account/multi-region architecture, eBPF basics (Cilium/Falco), incident-command skills (IC for majors)
- Own: on-call quality ("are we responding faster than before?"), architecture reviews, mentoring juniors
- Certify: CKA + one cloud professional cert (now company-funded)

## Senior → Lead/Staff (Years 4–7)

- Scope shift: from systems to people and direction — SLOs for teams, platform adoption metrics, cost programs, security compliance programs (SOC2/ISO hooks)
- Communication layers up: exec dashboards, budget talks, incident postmortems for the CTO
- Platform/architecture decisions: "which tools we standardize on" with a written rationale
- Skills: finance literacy (FinOps), vendor evaluation, drafting internal RFCs

## Lead → Architect / Principal (Years 7+)

- You design the 3-year infrastructure direction: multi-cloud strategy, data residency, disaster-recovery architecture, AI-infra evolution (GPU clusters, model serving pipelines)
- Industry presence: KubeCon talks, CNCF working groups, open-source maintainership of one tool, teaching
- Money: principal/architect comp sits 1.5–2.5x mid-level; AI-infra specialists command the frontier

## Specializations (choose one by Year 3)

1. Platform Engineering — IDPs, golden paths, developer experience (fastest growth)
2. SRE — reliability as product (SLO literacy, chaos engineering)
3. DevSecOps — policy-as-code, supply chain security (compliance-driven demand)
4. MLOps / ML Infra — GPU fleets, model serving, LLMOps (highest premium)
5. FinOps — cost engineering, rightsizing, budget automation (quietly exploding)
6. Security Engineering / Cloud Security — offense-adjacent defense (pentest + compliance track)

## Future technologies to watch (start tracking in Year 1)

- eBPF (Cilium as the default CNI question), WebAssembly runtimes at the edge, OpenTelemetry as universal telemetry, GitOps 2.0 (fleet management), AI-assisted SRE (anomaly detection + auto-remediation), serverless-in-production at scale, infrastructure-as-software (Pulumi-style + imperative bootstraps), K8s-On-Edge, internal AI infrastructure (RAG serving + GPU scheduling)

## The one habit that compounds everything

Post-mortem/technical writing at work, blog posts publicly, and open-source presence — in the DevOps market, your writing IS your career capital from day 1 to principal
---

# Part 19 — 180-Day Action Plan

Day-by-day execution of Part 3. Each line = the day's minimum; anything extra is bonus. Daily cadence: 2h learn / 2.5h build / 1h notes+commit / 0.5h drills. Sundays = review + zero-stress light reading.

## Days 1–28 (Weeks 1–4) — Linux · Git · Bash

- **D1** — Install WSL2 + Ubuntu; VS Code; first 20 commands; create GitHub account; first commit. Deliverable: screenshots of terminal + profile.
- **D2** — Navigation + file ops drills; write-your-own cheat sheet day 1. Deliverable: 10 commands from memory.
- **D3** — Permissions (chmod/chown/umask) + vim survival. Deliverable: vim-cheat sheet note.
- **D4** — grep/pipes/redirection; Bandit levels 0–3. Deliverable: 4 bandit flags.
- **D5** — man pages + help discipline; Bandit 4–5. Deliverable: 15 commands memorized.
- **D6** — Mini-project: Daily Log script (cron timestamps). Deliverable: repo `devops-labs` day 1.
- **D7** — Review: 20-min quiz, cheat sheet refresh, write "what I learned this week". Milestone: Linux basics done.
- **D8** — Processes (ps/top/kill); systemd intro. Deliverable: service started/stopped.
- **D9** — Users/groups/sudo; journalctl. Deliverable: created+locked user.
- **D10** — SSH keys + config end-to-end. Deliverable: key-only login works.
- **D11** — Networking tools (ip/ss/curl/dig). Deliverable: traces a port issue.
- **D12** — cron/timers + awk/sed basics. Deliverable: scheduled task running.
- **D13** — Oracle Cloud VM + hardening (no root, keys only). Deliverable: hardened VM doc.
- **D14** — Review + Bandit 6–15. Milestone: remote Linux operator.
- **D15** — Git core (init/clone/add/commit/log). Deliverable: 10 commits in journal repo.
- **D16** — Branches/merges + Learn Git Branching levels 1–3. Deliverable: all levels.
- **D17** — Remotes + GitHub PR flow; first PR to yourself. Deliverable: merged DIY PR.
- **D18** — Merge vs rebase practice + conflict surgery. Deliverable: solved-conflict note.
- **D19** — GitHub Skills: Intro + Markdown courses. Deliverable: 2 skill badges.
- **D20** — Journal → GitHub Pages site (portfolio shell). Deliverable: live URL.
- **D21** — Review + 5-min merge-vs-rebase essay. Milestone: Git fluency; streak = 21.
- **D22** — Bash syntax: vars, conditionals. Deliverable: 3 scripts.
- **D23** — Loops + functions + exit codes. Deliverable: script with proper exits.
- **D24** — Command substitution + strings; ShellCheck install. Deliverable: linted script.
- **D25** — Error handling: set -euo pipefail + traps. Deliverable: bulletproof base script.
- **D26** — jq/sed/awk deeper + HackerRank shell (5). Deliverable: 5 solved.
- **D27** — Mini-project: Backup & Rotate (reuse, idempotent). Deliverable: live script + README.
- **D28** — Review + refactor old scripts to -euo pipefail. Milestone: Bash automator.

## Days 29–56 (Weeks 5–8) — Python · Docker

- **D29** — Python: syntax + data structures. Deliverable: 10 tiny scripts.
- **D30** — Files + functions + modules. Deliverable: 3-module project.
- **D31** — venv/pip + error handling. Deliverable: frozen env file.
- **D32** — HTTP requests + JSON/YAML handling. Deliverable: API caller script.
- **D33** — argparse + pytest first tests. Deliverable: 5 passing tests.
- **D34** — Mini-project: System Report over SSH → webhook. Deliverable: running + README.
- **D35** — Review + LeetCode easy x2. Milestone: Python automation level.
- **D36** — Docker concepts: containers vs VMs; first run (nginx). Deliverable: running container.
- **D37** — docker run flags + logs/exec/ps. Deliverable: inspected container.
- **D38** — Dockerfile: build your Flask app image. Deliverable: image on disk.
- **D39** — Ports + volumes + .dockerignore. Deliverable: persisted data proof.
- **D40** — Multi-stage + non-root + HEALTHCHECK; image <150MB. Deliverable: slim image.
- **D41** — Play with Docker labs (3 scenarios) + trivy scan. Deliverable: scan report.
- **D42** — Review + publish to Docker Hub/GHCR. Milestone: image shipped.
- **D43** — Compose: services/networks/volumes. Deliverable: 2-service stack.
- **D44** — depends_on + healthchecks + env vars. Deliverable: healthy compose stack.
- **D45** — Voting-app study: read every service. Deliverable: architecture note.
- **D46** — Your Full Local Stack: app + Postgres + Redis + adminer. Deliverable: compose up green.
- **D47** — Dev vs prod overrides + profiles. Deliverable: two-env compose.
- **D48** — Build 2nd app (nginx static + certbot draft). Deliverable: compose x2.
- **D49** — Review + network diagram of your stack. Milestone: compose fluent.
- **D50** — GHCR publish pipeline (local script) + tagging strategy. Deliverable: tagged images.
- **D51** — trivy in the flow: fail on HIGH. Deliverable: gate working.
- **D52** — BuildKit secrets (no ARG secrets). Deliverable: secret-safe build.
- **D53** — Resource limits + read-only rootfs. Deliverable: hardened container.
- **D54** — 12-factor review of your app. Deliverable: written audit.
- **D55** — Mini-project: Secure Image Pipeline (build→scan→push). Deliverable: README + gate proof.
- **D56** — Review + Dockerfile best-practice quiz. Milestone: container-ready. LeetCode count ≥ 15.

## Days 57–84 (Weeks 9–12) — CI/CD · AWS

- **D57** — CI vs CD; first Actions workflow (lint). Deliverable: green lint badge.
- **D58** — Triggers + jobs + steps; runner basics. Deliverable: two-job workflow.
- **D59** — Secrets + environments + approvals. Deliverable: staged env deployment.
- **D60** — Matrix builds + caching + artifacts. Deliverable: matrix report artifact.
- **D61** — Add tests + hadolint + trivy to pipeline. Deliverable: gate chain.
- **D62** — OIDC (or SSH deploy) to your VM; deploy job. Deliverable: auto-deploy live.
- **D63** — Review + end-to-end write-up (commit→prod). Milestone: CI/CD = skill 1 done.
- **D64** — GitLab CI: project + first pipeline. Deliverable: green GitLab pipeline.
- **D65** — stages/rules/environments/artifacts. Deliverable: GitLab mirror.
- **D66** — Deploy strategies theory (blue/green, canary, rolling). Deliverable: essay.
- **D67** — Canary demo build (weighted proxy). Deliverable: canary script.
- **D68** — Jenkins: what/where/why (concepts). Deliverable: 1-page notes.
- **D69** — GitLab CI for pipeline #2 complete. Deliverable: mirror green.
- **D70** — Review + strategy comparison table. Milestone: two CI tools.
- **D71** — AWS account + MFA + billing alarm (first!). Deliverable: alarm armed.
- **D72** — IAM: users/groups/roles/policies; least privilege note. Deliverable: policy exercise.
- **D73** — VPC: subnets/routes/IGW/NAT/SG vs NACL. Deliverable: whiteboard diagram.
- **D74** — EC2: instances/AMIs/key pairs/user-data via CLI. Deliverable: CLI-created instance.
- **D75** — S3: buckets/versioning/lifecycle/presigned. Deliverable: locked bucket.
- **D76** — freeCodeCamp AWS CP course chunk 1 (IAM/S3/EC2 forward). Deliverable: timeline notes.
- **D77** — Review + $0 cost check + Tiny Web Farm begins. Milestone: AWS core 1.
- **D78** — RDS PostgreSQL + connect app. Deliverable: app→RDS working.
- **D79** — Lambda + IAM for functions. Deliverable: hello-lambda via CLI.
- **D80** — CloudWatch: logs/metrics/alarms/dashboards. Deliverable: 2 alarms.
- **D81** — ALB + target groups. Deliverable: ALB serving app.
- **D82** — Autoscaling: launch template + policies. Deliverable: ASG 2–4.
- **D83** — Stress test: scale-out demo + CloudWatch proof. Deliverable: scaling evidence.
- **D84** — Review + cost check ($0) + architecture diagram. Milestone: resilient cloud site.

## Days 85–112 (Weeks 13–16) — Architecture · Terraform

- **D85** — 3-tier architecture + statelessness. Deliverable: whiteboard notes.
- **D86** — Serverless patterns (API GW/Lambda/DynamoDB). Deliverable: serverless sketch.
- **D87** — Event-driven: S3→Lambda→SQS→worker + DLQ. Deliverable: dead-letter queue demo.
- **D88** — Well-Architected pillars reading. Deliverable: 1-page summary.
- **D89** — Mini-project: Event Pipeline complete + docs. Deliverable: repo + flow diagram.
- **D90** — Review + cost analysis ($0 proof). Milestone: project 2 done.
- **D91** — AWS security: CloudTrail + S3 policies + SSM. Deliverable: audit log active.
- **D92** — KMS basics + cross-account roles idea. Deliverable: encryption note.
- **D93** — Azure map: resource groups/VNet/AKS/Entra. Deliverable: comparison table part 1.
- **D94** — GCP map: projects/VPC/GKE/IAM. Deliverable: comparison table complete.
- **D95** — Locked-Down Account checklist applied. Deliverable: evidence screenshots.
- **D96** — Review + security quiz (SG vs NACL vs IAM). Milestone: security-aware cloud user.
- **D97** — Terraform basics: init/plan/apply/destroy. Deliverable: first resource via TF.
- **D98** — Resources + data sources + first web farm. Deliverable: TF re-creates Web Farm.
- **D99** — Variables + locals + outputs. Deliverable: parameterized stack.
- **D100** — State: read it, understand it. Deliverable: state explainer note.
- **D101** — fmt/validate + lifecycle + tags everywhere. Deliverable: lint-clean project.
- **D102** — Mini-project: TF Web Farm (full rewrite). Deliverable: destroy-rebuild proof.
- **D103** — Review + re-apply from scratch unaided. Milestone: plan/apply fluent.
- **D104** — Remote state: S3 + DynamoDB locking. Deliverable: locked remote state.
- **D105** — Workspaces + environments. Deliverable: dev/prod workspaces.
- **D106** — Modules: write network/compute/storage modules. Deliverable: module library.
- **D107** — Module versions + registry publish (local). Deliverable: versioned modules.
- **D108** — terraform import + drift detection. Deliverable: drifted resource found.
- **D109** — checkov scan + fixes. Deliverable: clean scan.
- **D110** — Concurrency demo: two-shell locking test. Deliverable: lock video.
- **D111** — Review + Terraform essay (state/lock/modules). Milestone: IaC professional-grade.
- **D112** — Soft-launch: first 3 applications + first LinkedIn post. Deliverable: applications sent.

## Days 113–140 (Weeks 17–20) — Ansible · Kubernetes · GitOps

- **D113** — Ansible: inventory + ad-hoc. Deliverable: ping all hosts.
- **D114** — Playbooks + modules + idempotency check. Deliverable: run twice, unchanged.
- **D115** — Handlers + templates (Jinja2). Deliverable: templated nginx config.
- **D116** — Roles: build a role (Docker + hardened SSH). Deliverable: reusable role.
- **D117** — Secrets: env files, never-in-git; Vault concepts. Deliverable: secrets policy note.
- **D118** — Mini-project: Config Stack (2 hosts + role). Deliverable: repo + idempotency proof.
- **D119** — Review + Terraform-vs-Ansible essay. Milestone: config mgmt done.
- **D120** — K8s architecture: control plane vs nodes. Deliverable: whiteboard.
- **D121** — kind cluster + kubectl basics (get/describe). Deliverable: cluster running.
- **D122** — Pods + deployments + replicasets. Deliverable: 3-replica app.
- **D123** — Services (ClusterIP/NodePort/LB) + labels. Deliverable: app reachable.
- **D124** — Probes: liveness/readiness/startup. Deliverable: probe behavior demo.
- **D125** — Killercoda labs (pods/deployments/services). Deliverable: 5 scenarios done.
- **D126** — Review + rollout undo drill. Milestone: first cluster operated.
- **D127** — ConfigMaps + Secrets. Deliverable: config-driven app.
- **D128** — Storage: PV/PVC + storage classes. Deliverable: persistent uploads.
- **D129** — Requests/limits + HPA. Deliverable: autoscaling demo.
- **D130** — Taints/tolerations/affinity + cordon/drain. Deliverable: maintenance demo.
- **D131** — Ingress + TLS via ingress-nginx. Deliverable: https reachable.
- **D132** — Troubleshooting runbook part 1 (CrashLoop/Pending/OOMKilled). Deliverable: runbook repo.
- **D133** — Review + broken-cluster drill (diagnose 2 faults). Milestone: day-2 operator.
- **D134** — Helm: charts/values/templates basics. Deliverable: first chart.
- **D135** — helm install/upgrade/rollback + dependencies. Deliverable: charted app.
- **D136** — ArgoCD install on kind. Deliverable: ArgoCD UI up.
- **D137** — GitOps: repo as source of truth; sync/self-heal. Deliverable: git-only deploy.
- **D138** — Drift war: drift manually, watch ArgoCD heal. Deliverable: drift video.
- **D139** — Convert app to Helm + ArgoCD cleanly. Deliverable: capstone repo takes shape.
- **D140** — Review + GitOps essay. Milestone: capstone project live.

## Days 141–168 (Weeks 21–24) — Production K8s · Observability · DevSecOps · Launch

- **D141** — RBAC: roles/bindings/service accounts. Deliverable: scoped SA demo.
- **D142** — Pod security + network policies. Deliverable: policy-applied app.
- **D143** — Upgrades + etcd backup awareness (Velero). Deliverable: backup drill notes.
- **D144** — kubectl debug + ephemeral containers + k9s. Deliverable: debug toolbox doc.
- **D145** — Chaos day: kill pods/nodes, recover. Deliverable: chaos report.
- **D146** — Battle-Tested Cluster: hardening checklist applied. Deliverable: checklist + runbook v2.
- **D147** — Review + killercoda advanced scenario. Milestone: production K8s confidence.
- **D148** — Prometheus: install (kube-prometheus-stack). Deliverable: targets scraping.
- **D149** — PromQL: rate/histogram_quantile drills. Deliverable: 3 queries explained.
- **D150** — Alerting: rules + Alertmanager. Deliverable: alert fires → notification.
- **D151** — Grafana dashboards: panels + variables. Deliverable: app dashboard.
- **D152** — Loki logs + labels. Deliverable: log view in Grafana.
- **D153** — OpenTelemetry concepts + SLO/SLI + error budget. Deliverable: SLO doc.
- **D154** — Reliability Dash project complete. Milestone: observability tier done.
- **D155** — DevSecOps: Semgrep in pipeline. Deliverable: SAST gate.
- **D156** — gitleaks: secret scanning gate. Deliverable: planted secret caught.
- **D157** — trivy + checkov as pipeline gates. Deliverable: full scan chain.
- **D158** — OWASP Top 10 awareness + DAST basics (ZAP). Deliverable: ZAP smoke scan.
- **D159** — Supply chain: lockfiles/pinned images/SBOM. Deliverable: SBOM generated.
- **D160** — Secure Pipeline project complete + scan matrix doc. Deliverable: repo + README.
- **D161** — Review + security quiz. Milestone: DevSecOps-ready.
- **D162** — Resume v2 + LinkedIn overhaul (Parts 9–10). Deliverable: live profile.
- **D163** — Portfolio site update + capstone README + demo video. Deliverable: video published.
- **D164** — GitHub profile pass: pins, badges, contribution map. Deliverable: polished profile.
- **D165** — Mock interview x2 (20-question set, out loud). Deliverable: 2 recordings reviewed.
- **D166** — Applications: 10 sent + 3 cold outreach + 1 post. Deliverable: tracker filled.
- **D167** — Applications: 10 sent + recruiter connects. Deliverable: 20+ total.
- **D168** — Full self-review vs Part 20 checklist. Milestone: job-search machine on.

## Days 169–180 — Full-Throttle Search & Iteration

- **D169** — 10 applications (fresh JDs <7 days) + 2 follow-ups. Deliverable: tracker.
- **D170** — 10 applications + 1 mock interview. Deliverable: interview notes.
- **D171** — Outreach quota (5 engineers/recruiters) + 1 post. Deliverable: replies noted.
- **D172** — 10 applications + fix resume from any feedback. Deliverable: resume v3.
- **D173** — Referral asks x3 + follow-ups. Deliverable: referral tracker.
- **D174** — 10 applications + 1 Whiteboard design drill. Deliverable: recorded drill.
- **D175** — Mock interview + 20 questions again (faster). Deliverable: time-to-answer improved.
- **D176** — 10 applications + 1 project polish (capstone docs). Deliverable: capstone v2.
- **D177** — Outreach + negotiate prep (salary research). Deliverable: range sheet.
- **D178** — 10 applications + interview (if any). Deliverable: whatever comes.
- **D179** — Review funnel: what converts; adjust keywords/roles. Deliverable: strategy v2.
- **D180** — Day 180 review + 90-day extension plan. Milestone: 60+ quality applications, 3+ interviews, portfolio live, ready for offers.

---

# Part 20 — Final Success Checklist

## Can build production-ready projects

- [ ] Dockerized app with multi-stage, non-root, healthchecked images shipped to GHCR
- [ ] Composed 4-service local stack with persistence and health checks
- [ ] Full CI/CD pipeline: lint → test → build → scan → push → deploy, with security gates
- [ ] Terraform environments with remote state, locking, modules, checkov-clean
- [ ] Kubernetes cluster with Helm, ArgoCD GitOps, HPA, TLS ingress, runbooks
- [ ] Prometheus + Grafana stack with alerts, Loki logs, SLOs
- [ ] Serverless event pipeline with DLQ and idempotency
- [ ] Every project documented (README formula from Part 8) and deployed

## Can solve interview problems

- [ ] 20 interview questions answered cold, 90-second format
- [ ] Live troubleshooting drill completed blind (diagnose without AI)
- [ ] 40–60 LeetCode problems + HackerRank Linux Shell track done
- [ ] 3 mock interviews completed (Pramp/AI); recordings reviewed
- [ ] System design: 3 patterns whiteboarded from memory (3-tier, GitOps, event-driven)

## Has certifications

- [ ] GitHub Skills badges earned (2+)
- [ ] One or more Tier-1 free certificates (freeCodeCamp DB, LFS101x, AWS Skill Builder badge)
- [ ] (Funded, optional) AWS CP + Terraform Associate planned

## Has GitHub portfolio

- [ ] 6 pinned repos, each with full README formula, badges, live links
- [ ] Daily commit streak 90+ days
- [ ] At least 1 merged open-source contribution (docs OK to start)
- [ ] gitleaks-swept (zero secrets)

## Has LinkedIn profile

- [ ] Keyworded headline, About with proof links, banner, Featured, Projects
- [ ] Open-to-Work set for recruiters; 50+ relevant connections
- [ ] 3+ posts/week rhythm running; at least 1 engagement going
- [ ] 15 cold outreaches sent; replies + follow-ups tracked

## Has resume

- [ ] ATS-safe single-column PDF, keyword-matched to target roles
- [ ] Projects section doubles as experience; numbers everywhere; links verified

## Has portfolio website

- [ ] Live site (GitHub Pages or equivalent) with hero, skills, projects, resume, blog
- [ ] Deployed via your own pipeline (it's also a project)

## Has capstone project

- [ ] K8s + GitOps capstone with architecture diagram, dashboards, war story, demo video
- [ ] Can demo in 3 minutes without notes

## Has open-source contributions

- [ ] 1+ merged PR (docs/test/code) in a CNCF or ecosystem project

## Has mock interview practice

- [ ] 5+ mock interviews total (Pramp/AI/peer); 2 recordings self-critiqued

## Has applied to jobs

- [ ] 60+ quality applications tracked in a spreadsheet with follow-up column
- [ ] 20+ cold outreaches;  5+ referral asks; 10+ recruiter conversations

## Ready for interviews

- [ ] Can present portfolio walkthrough under 10 minutes
- [ ] Behavioral: 6 STAR stories with numbers
- [ ] HR answers practiced (self-intro 90s, salary range, "why us")

## Ready to receive offers

- [ ] Salary research done for your market; counter-offer basics known
- [ ] Reference list ready (peers you taught, clients, mentors)
- [ ] 90-day first-job learning plan drafted (Part 18 junior track)

---

# Job Readiness Scorecard

Readiness % = how close you are to being employable at each point, plus milestones. The honest rule: **start soft-applying at Month 3 (Week 12–13), go full throttle when you reach 80%.**

| Month | Readiness | Milestones achieved | Criteria to advance |
|---|---|---|---|
| Month 1 | ~15% | Linux/Git/Bash foundations, first repo streak, cheat sheets, Bandit 15 levels | Can explain permissions, pipes, SSH; commits daily |
| Month 2 | ~35% | Python scripts + Docker (multi-stage images), compose stacks, first pipeline, trivy gates | Can containerize any small app; image <200MB; basic CI green |
| Month 3 | ~55% | Full CI/CD + GitLab CI, AWS core (VPC/EC2/S3/IAM via CLI), serverless events, Terraform intro, soft-launch applications start | Can rebuild a VPC in Terraform; explains deploy strategies; 3+mock interviews pending |
| Month 4 | ~70% | Terraform modules/remote state, Ansible, Kubernetes core + day-2 ops, GitOps + ArgoCD, capstone live | Can diagnose CrashLoopBackOff blind; GitOps deploy on git commit; SLOs defined |
| Month 5 | ~85% | Observability stack + SLOs, DevSecOps gates, full portfolio polished, LinkedIn live, 30+ applications, 3+ interview loops | 20 questions cold; full application funnel running; mock interview score 7/10+ |
| Month 6 | ~95–100% | 60+ applications, referrals + outreach flowing, offers in negotiation | 2+ final-round interviews; salary range prepared; offer in hand |

## Decision guide — when to start applying

- **Internships/apprenticeships:** start Month 3 (months of lead time; they hire cohorts early)
- **Full-time entry roles:** Month 5+, once: capstone live + 20 questions cold + one mock interview at 7/10
- **Freelance:** anytime from Month 2 (services = what you've already built in the lab)
- **Do not wait for "perfection"** — recruiters hire trajectory, and your live portfolio + streak IS the proof of trajectory

## The 10% rule that decides salary vs. rejection

You are employable when 10 strangers could run your Quickstart, watch your demo video, and say "this person runs systems." Everything else (certificates, resumes, posts) just makes sure they find you. Build those systems today.

---

*End of roadmap. License: MIT. Feel free to fork, remix, and share.*
