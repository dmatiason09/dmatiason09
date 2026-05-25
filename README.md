<!-- Header -->
<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=28&duration=3500&pause=1200&color=00D9FF&center=true&vCenter=true&width=760&lines=Dennis+Ortiz+%E2%80%94+Cloud+Security+Engineer+in+training;AWS+%C2%B7+Terraform+%C2%B7+Python+%C2%B7+DevSecOps;Building+evidence%2C+not+claims.)](https://github.com/dmatiason09)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/dennis-ortiz-8a1a1a3a7)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dmatiason09@gmail.com)
[![Profile Views](https://komarev.com/ghpvc/?username=dmatiason09&style=for-the-badge&color=00D9FF)](https://github.com/dmatiason09)

</div>

---

## About

Systems Engineering student at **Universidad de Lima** (5th semester), based in **Lima, Peru**. I'm on a 24-month transition into **Cloud Security Engineering** — focusing on IAM, infrastructure-as-code security, and DevSecOps tooling on AWS first, Azure next.

I learn in public. Every concept I study lands in a lab or a tool published on this profile, with code, tests, and references to recognized frameworks.

- Currently building **[`multicloud-iam-lab`](https://github.com/dmatiason09/multicloud-iam-lab)** — IAM hardening + DevSecOps pipeline
- Studying for **CompTIA Security+** and **CCSK Foundation**
- Languages: Spanish (native) · English (B2)
- Open to **junior Cloud Security Engineer** roles, on-site Lima or remote

---

## Featured Lab — `multicloud-iam-lab` v1.0

A hands-on lab that detects and remediates IAM misconfigurations on AWS, with a built-in DevSecOps pipeline.

| What it does | Stack |
|---|---|
| Paired Terraform modules (`vulnerable/` vs `hardened/`) deploying five misconfigured AWS resources side-by-side with their secure counterparts | Terraform 1.6+, AWS Provider 5.x |
| Python scanner detecting five IAM / S3 findings: MFA gaps, wildcard policies, public buckets, permissive role trusts, stale access keys | Python 3.11, boto3, moto, pytest (87% coverage) |
| GitHub Actions pipeline auditing the repo on every PR with six jobs | Checkov, Semgrep, gitleaks, Trivy, pytest |

Findings map to **AWS Foundational Security Best Practices**, **CIS AWS Benchmark v3.0**, and **MITRE ATT&CK**.

[![security-scan](https://github.com/dmatiason09/multicloud-iam-lab/actions/workflows/security-scan.yml/badge.svg)](https://github.com/dmatiason09/multicloud-iam-lab/actions/workflows/security-scan.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/dmatiason09/multicloud-iam-lab/blob/main/LICENSE)
[![v1.0.0](https://img.shields.io/github/v/tag/dmatiason09/multicloud-iam-lab?label=release&color=00D9FF)](https://github.com/dmatiason09/multicloud-iam-lab/releases)

→ **[Explore the lab](https://github.com/dmatiason09/multicloud-iam-lab)**

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
- NIST Cybersecurity Framework 2.0 (in study)

---

## Learning roadmap

Public commitments. If a milestone slips, it slips on this README too.

| When | Milestone |
|---|---|
| **Q3 2026** | CompTIA Security+ · CCSK Foundation |
| **Q4 2026** | AWS Certified Security – Specialty |
| **Q4 2026** | `multicloud-iam-lab` v1.1 — Azure parity + ephemeral CI deploy |
| **Q1 2027** | Threat detection lab (CloudTrail + GuardDuty + Defender for Cloud) |
| **Q2 2027** | CKS — Certified Kubernetes Security Specialist |
| **2027** | First junior role or internship in Cloud Security |

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
