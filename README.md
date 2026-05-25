<!-- Header -->
<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=28&duration=3500&pause=1200&color=00D9FF&center=true&vCenter=true&width=760&lines=Dennis+Ortiz+%E2%80%94+Cloud+Security+Engineer+in+training;AWS+%C2%B7+Terraform+%C2%B7+Python+%C2%B7+DevSecOps;Building+evidence%2C+not+claims.)](https://github.com/dmatiason09)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/dennis-ortiz-8a1a1a3a7)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dmatiason09@gmail.com)
[![Profile Views](https://komarev.com/ghpvc/?username=dmatiason09&style=for-the-badge&color=00D9FF)](https://github.com/dmatiason09)

</div>

---

## About

Systems Engineering student at **Universidad de Lima**, based in **Lima, Peru**. Building toward **Cloud Security Engineering** — focusing on IAM, infrastructure-as-code security, and DevSecOps tooling on AWS, with Azure on the horizon.

I learn by building. Code, tests, and references to recognized frameworks live in every project I publish.

- Open-source labs: **[`multicloud-iam-lab`](https://github.com/dmatiason09/multicloud-iam-lab)** (prevention) and **[`cloudtrail-threat-detector`](https://github.com/dmatiason09/cloudtrail-threat-detector)** (detection)
- Languages: Spanish (native) · English (B2)
- Open to **junior Cloud Security Engineer** roles and internships — on-site Lima or remote

---

## Featured Labs

Two paired projects covering the prevention–detection axis of cloud security engineering.

### `multicloud-iam-lab` v1.0 — Prevention

A hands-on lab that detects and remediates IAM misconfigurations on AWS, with a built-in DevSecOps pipeline.

- **Paired Terraform modules** (`vulnerable/` vs `hardened/`) deploying five misconfigured AWS resources side-by-side with their secure counterparts.
- **Python scanner** detecting five IAM / S3 findings (MFA gaps, wildcard policies, public buckets, permissive role trusts, stale access keys). 87% test coverage with moto-mocked AWS.
- **GitHub Actions pipeline** auditing the repo with Checkov, Semgrep, gitleaks, Trivy, and pytest.

Findings map to **AWS FSBP**, **CIS Benchmark v3.0**, and **MITRE ATT&CK**.

[![multicloud-iam-lab CI](https://github.com/dmatiason09/multicloud-iam-lab/actions/workflows/security-scan.yml/badge.svg)](https://github.com/dmatiason09/multicloud-iam-lab/actions/workflows/security-scan.yml)
[![v1.0.0](https://img.shields.io/github/v/tag/dmatiason09/multicloud-iam-lab?label=release&color=00D9FF)](https://github.com/dmatiason09/multicloud-iam-lab/releases)

→ **[Explore the lab](https://github.com/dmatiason09/multicloud-iam-lab)**

### `cloudtrail-threat-detector` v1.0 — Detection

A pure-stdlib Python CLI that ingests AWS CloudTrail logs and detects five attacker behaviors with hardcoded rules.

- **Five detection rules** (3 stateless, 2 stateful sliding-window) covering privilege escalation, reconnaissance, weak authentication, brute force, and unusual region activity.
- **Bundled samples** simulating each attack scenario plus a benign baseline — try the tool without an AWS account.
- **Self-auditing pipeline** (Semgrep, gitleaks, Trivy, pytest, sample validation). 95% test coverage.

Each detection maps to a **MITRE ATT&CK** technique and ships with a response runbook in the catalog.

[![cloudtrail-threat-detector CI](https://github.com/dmatiason09/cloudtrail-threat-detector/actions/workflows/security-scan.yml/badge.svg)](https://github.com/dmatiason09/cloudtrail-threat-detector/actions/workflows/security-scan.yml)
[![v1.0.0](https://img.shields.io/github/v/tag/dmatiason09/cloudtrail-threat-detector?label=release&color=00D9FF)](https://github.com/dmatiason09/cloudtrail-threat-detector/releases)

→ **[Explore the lab](https://github.com/dmatiason09/cloudtrail-threat-detector)**

---

## Tech Stack

**Cloud**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=FF9900)
![Azure (in progress)](https://img.shields.io/badge/Azure_(in_progress)-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)

**Infrastructure as Code**

![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)

**Security tooling**

![Checkov](https://img.shields.io/badge/Checkov-1A1F36?style=flat-square)
![Semgrep](https://img.shields.io/badge/Semgrep-1A1F36?style=flat-square)
![gitleaks](https://img.shields.io/badge/gitleaks-1A1F36?style=flat-square)
![Trivy](https://img.shields.io/badge/Trivy-1904DA?style=flat-square&logo=aquasec&logoColor=white)
![moto](https://img.shields.io/badge/moto-1A1F36?style=flat-square)

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

**Platforms & workflow**

![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## Security frameworks I work with

When I write detection logic or remediation, I map findings back to recognized baselines so the work is interview-ready and audit-friendly:

- AWS Foundational Security Best Practices (FSBP)
- CIS AWS Benchmark v3.0
- MITRE ATT&CK (Cloud techniques)
- NIST Cybersecurity Framework 2.0

---

## Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=dmatiason09&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=00D9FF&icon_color=00D9FF" alt="GitHub Stats" height="170"/>
&nbsp;
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=dmatiason09&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=00D9FF" alt="Top Languages" height="170"/>

[![GitHub Streak](https://streak-stats.demolab.com?user=dmatiason09&theme=tokyonight&hide_border=true&background=0D1117&ring=00D9FF&fire=00D9FF&currStreakLabel=00D9FF)](https://git.io/streak-stats)

</div>

---

## Get in touch

Open to junior Cloud Security Engineer roles, internship opportunities, and pair-learning collaborations on AWS / Azure security labs.

<div align="center">

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/dennis-ortiz-8a1a1a3a7)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dmatiason09@gmail.com)

</div>
