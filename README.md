<div align="center">

# André Sacilotto Santos

### `from kernel cycles to cloud regions`

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=18&duration=3500&pause=900&color=58A6FF&center=true&vCenter=true&width=720&lines=Performance+%26+Infrastructure+Engineer+%40+Dell+Innovation+Center;MSc+Candidate+in+Parallel+%26+Distributed+Systems+%40+PUCRS;IEEE+PDP+2023+Published+Researcher;Profiling+the+kernel%2C+provisioning+the+cloud.)](https://git.io/typing-svg)

<p>
  <a href="https://www.linkedin.com/in/saccilotto/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:sacilotto.andre@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://doi.org/10.1109/PDP59025.2023.00033"><img src="https://img.shields.io/badge/IEEE_PDP_2023-00629B?style=for-the-badge&logo=ieee&logoColor=white" /></a>
  <a href="https://orcid.org/0000-0002-1639-3238"><img src="https://img.shields.io/badge/ORCID-A6CE39?style=for-the-badge&logo=orcid&logoColor=white" /></a>
  <img src="https://img.shields.io/badge/Porto_Alegre,_BR-009C3B?style=for-the-badge&logo=googlemaps&logoColor=white" />
</p>

</div>

---

## `> whoami`

I build automation platforms that make database performance benchmarking **reproducible at scale**. By day, I work with Terraform, Ansible, Kubernetes, and Go at the **Dell Innovation Center**. By night (well, also by day), I research **container interference profiling** for my Master's at PUCRS — figuring out why your "isolated" workload is mysteriously 30% slower in production.

Former classical violinist who traded obsessing over intonation for obsessing over **p99 latency**. The pursuit of mastery carried over — my teammates once called me **"The Infra Wizard"** during project retrospectives, and I'm still not sure I've lived up to it. 🧙

> **TL;DR** — I bridge academic rigor with production engineering. Bring me your unreproducible benchmark, your flaky CI, your "it works on my cluster," and let's measure our way out.

---

## `> currently_building`

<table>
<tr>
<td width="50%" valign="top">

### 🛠️ At Dell Innovation Center
*Performance & Automation Engineer*

End-to-end automation for distributed database benchmarking across **Oracle**, **MongoDB**, and **PostgreSQL** — at scale, fully reproducible.

- Python + Ansible provisioning (hours → minutes)
- Containerized HammerDB / YCSB pipelines
- Production observability: Prometheus + Grafana
- Custom **Terraform providers in Go** for proprietary infra
- Kubernetes-based environment automation

</td>
<td width="50%" valign="top">

### 🔬 MSc Research — IntP
*Advisor: Prof. Cesar De Rose · PPGCC-PUCRS · 2026–2027*

Kernel-level **performance interference profiler** for containerized environments — answering *why* noisy neighbors hurt, not just *that* they do.

- Multi-variant comparison: SystemTap, procfs, bpftrace, eBPF/CO-RE
- Reproducible noise injection (CPU, mem, net, I/O)
- Integration with HDFS / Spark workloads on PUCRS LAD
- Targeting Linux 6.8+ stable surface

</td>
</tr>
</table>

---

## `> pinned_signal`

<table>
<tr>
<td width="50%" valign="top">

#### 🧪 [`intp-comparison`](https://github.com/ggrv-intp/intp-comparison)
Linux interference profiler with **multi-variant comparison** of SystemTap, procfs, bpftrace, and eBPF/CO-RE instrumentation. The empirical core of my Master's.
`Shell` `eBPF` `SystemTap` `C`

</td>
<td width="50%" valign="top">

#### 🌲 [`AGES-Pro-Mata/infrastructure`](https://github.com/AGES-Pro-Mata/infrastructure)
Multi-cloud IaC (**AWS primary + Azure DR**) for the Pro-Mata ecological research center's hospitality platform. Led 8+ devs as PM & Infra Architect.
`Terraform` `GitLab CI` `Grafana` `Metabase`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### ⛏️ [`Mineclifford-Server`](https://github.com/Saccilotto/Mineclifford-Server)
Deploy and manage **Minecraft servers on AWS/Azure** from a single CLI command. Terraform provisions, Ansible configures, Docker runs the game.
`Shell` `Terraform` `Ansible` `Docker`

</td>
<td width="50%" valign="top">

#### 🌱 [`planta-infra`](https://github.com/Saccilotto/planta-infra)
**Cloud-agnostic** IaC + CaC for the CP-Planta industrial management app — deploy the same stack to AWS or Azure with one switch.
`Terraform` `Ansible` `Docker Swarm` `PostgreSQL HA`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🚀 [`gitops`](https://github.com/Saccilotto/gitops)
**EKS cluster** provisioned with Terraform; observability stack installed via **ArgoCD + Helm**. The "do it the boring, correct way" reference.
`HCL` `ArgoCD` `Helm` `Kubernetes`

</td>
<td width="50%" valign="top">

#### 🛰️ [`intp`](https://github.com/ggrv-intp/intp)
Hybrid **v2 + eBPF/CO-RE** interference profiler — `libintp` + CLI, Meson-built, with a plugin ABI for GPU, DB, observability, and scheduler extensions.
`C` `eBPF` `Meson` `Plugin ABI`

</td>
</tr>
</table>

---

## `> stack`

<div align="left">

**Languages**
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Shell](https://img.shields.io/badge/Shell-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

**Infrastructure as Code**
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Podman](https://img.shields.io/badge/Podman-892CA0?style=flat-square&logo=podman&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=flat-square&logo=argo&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white)

**Cloud & Platforms**
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Oracle Cloud](https://img.shields.io/badge/Oracle_Cloud-F80000?style=flat-square&logo=oracle&logoColor=white)
![Proxmox](https://img.shields.io/badge/Proxmox-E57000?style=flat-square&logo=proxmox&logoColor=white)
![KVM](https://img.shields.io/badge/KVM-FFCA28?style=flat-square&logo=qemu&logoColor=black)

**Observability & Benchmarking**
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![HammerDB](https://img.shields.io/badge/HammerDB-E04E2A?style=flat-square&logoColor=white)
![YCSB](https://img.shields.io/badge/YCSB-1A73E8?style=flat-square&logoColor=white)
![eBPF](https://img.shields.io/badge/eBPF-005571?style=flat-square&logoColor=white)
![SystemTap](https://img.shields.io/badge/SystemTap-E61E26?style=flat-square&logoColor=white)

**Backend & Data**
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=spring&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-4285F4?style=flat-square&logo=google&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)

**CI/CD & AI**
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab_CI-FC6D26?style=flat-square&logo=gitlab&logoColor=white)
![Claude](https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=anthropic&logoColor=white)
![Copilot](https://img.shields.io/badge/Copilot-000000?style=flat-square&logo=githubcopilot&logoColor=white)

</div>

---

## `> publication`

> 📄 **Santos, A. S., et al.** *"A Latency, Throughput, and Programmability Perspective of GrPPI for Streaming on Multi-cores."*
> 31st Euromicro International Conference on Parallel, Distributed and Network-Based Processing (**PDP**), IEEE, 2023.
> [`doi:10.1109/PDP59025.2023.00033`](https://doi.org/10.1109/PDP59025.2023.00033)

---

## `> by_the_numbers`

<div align="center">

<!--
  Generated daily by lowlighter/metrics via GitHub Actions.
  See .github/workflows/metrics.yml — no external runtime deps.
-->

![Metrics — overview](./metrics.svg)

![Metrics — isocalendar](./metrics.isocalendar.svg)

![Metrics — languages](./metrics.languages.svg)

</div>

---

<div align="center">

### `> say_hi`

I'm open to **DevOps**, **Platform**, **Infrastructure**, and **Backend** roles — especially where performance and reliability *actually* matter.

**[LinkedIn](https://www.linkedin.com/in/saccilotto/)** · **[Email](mailto:sacilotto.andre@gmail.com)** · **[IEEE Publication](https://doi.org/10.1109/PDP59025.2023.00033)** · **[ORCID](https://orcid.org/0000-0002-1639-3238)**

<sub>*"Measure twice, provision once."*</sub>

</div>
