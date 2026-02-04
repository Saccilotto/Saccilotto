# André Sacilotto Santos

**Backend Engineer | Infrastructure Automation | Systems Performance Research**

Building high-performance systems at the intersection of academic research and production engineering. Currently developing automation platforms for database performance analysis at Dell Innovation Center while conducting graduate research in container interference profiling and Linux kernel instrumentation.

**Porto Alegre, Brazil** | [LinkedIn](https://linkedin.com/in/saccilotto) | [Email](mailto:sacilotto.andre@gmail.com) | [IEEE Publication](https://doi.org/10.1109/PDP59025.2023.00033)

---

## About

I specialize in infrastructure automation, high-performance backend systems, and performance engineering. My work combines rigorous academic research methodologies with practical production experience, allowing me to approach complex systems problems from both theoretical and implementation perspectives.

**Current Focus:**
- Building automation platforms for comparative database benchmarking (Oracle, MongoDB, PostgreSQL)
- Graduate research in systems performance and container interference profiling (IntP)
- Completing accelerated M.Sc. program (Integra-Pós G+1) at PPGCC-PUCRS, graduating March 2027
- Infrastructure as Code with Terraform, Ansible, and Kubernetes

**What makes my approach different:** I bring academic rigor to production engineering. My IEEE publication on parallel processing performance analysis taught me systematic benchmarking and experimental design. I apply these same methodologies when optimizing database workloads, designing infrastructure, or developing profiling tools for kernel-level performance analysis. The combination of graduate coursework completed during my undergraduate degree and concurrent industry experience at Dell Innovation Center provides a unique technical depth that typically requires many more years to develop.

---

## Core Expertise

### Infrastructure & Performance Engineering
Building and automating scalable infrastructure with focus on performance and reliability. Experience ranges from custom Terraform providers in Go to complete observability stacks for production systems.

**Key Technologies:** Terraform, Ansible, Kubernetes, Docker/Podman, Prometheus, Grafana, Python, Go

**Representative Work:**
- Architected Python/Ansible automation platform for distributed database benchmarking
- Developed containerized stress-testing pipelines with HammerDB and YCSB
- Built custom Terraform providers in Go for specialized infrastructure needs
- Implemented multi-cloud disaster recovery architectures (AWS primary, Azure failover)

### Backend Development & APIs
High-performance backend systems designed for scalability and maintainability. Strong focus on database optimization and API design.

**Key Technologies:** Go, NestJS, TypeScript, Node.js, C++, RESTful APIs, gRPC

**Representative Work:**
- Backend architecture for multi-tenant reservation platforms with PostgreSQL replication
- RESTful APIs following Clean Architecture and SOLID principles
- Database optimization across PostgreSQL, MongoDB, and Oracle workloads

### Research & Performance Analysis
Academic research background in parallel processing and network protocols. Applied research methodologies to production performance problems.

**Active Research Areas:**
- Low-latency network protocols for live music collaboration and cloud gaming
- Comparative database performance analysis under high-concurrency scenarios
- Parallel processing optimization with C++, Intel TBB

**Publication:** Co-authored IEEE PDP 2023 paper on parallel processing platform performance characteristics

---

## Current Work

### Performance & Automation Engineer | Dell Innovation Center (April 2024 - Present)

Building automation infrastructure for systematic database performance evaluation.

**Technical Approach:**
The platform uses Python and Ansible for environment provisioning, containerized workloads for consistent testing, and Prometheus/Grafana for metrics collection. This allows reproducible experiments comparing Oracle, MongoDB, and PostgreSQL under various load patterns.

**Key Contributions:**
- Architected end-to-end automation eliminating manual configuration in benchmark workflows
- Implemented observability stack capturing system, database, and network metrics in real-time
- Developed custom Terraform providers extending automation capabilities
- Designed containerized testing environments ensuring experiment reproducibility

**Stack:** Python, Go, Ansible, Terraform, Kubernetes, Docker, Oracle, MongoDB, PostgreSQL, Prometheus, Grafana

---

## Academic Research

### PPGCC-PUCRS Graduate Student (March 2026 - March 2027)

Pursuing M.Sc. in Computer Science through the **Integra-Pós G+1 accelerated program**, which allowed me to complete core coursework during my undergraduate studies. Selected for this program based on academic merit (IEEE publication), I am on track to complete my Master's in one year instead of two, with thesis defense expected in March-April 2027.

**Thesis Research:** "Interference Profiling Tools for Container Scheduling in Modern Linux Systems"  
**Advisor:** Prof. Cesar Augusto Fonticielha De Rose  
**Research Group:** GPPD (Parallel and Distributed Processing Group)

**Research Focus:**

Working on IntP (Interference Profiler), a systems-level tool for measuring performance interference in containerized environments. The research addresses fundamental compatibility challenges between existing profiling tools and modern Linux kernels (6.8+), while exploring the transition from SystemTap to eBPF as a more robust, forward-compatible solution.

**Core Technical Work:**
- Adapting interference profiling for kernel 6.8.0+ (network, I/O, memory bandwidth, cache, CPU metrics)
- Comparative analysis of SystemTap vs eBPF backends for container-native profiling
- Integration with container scheduling systems for interference-aware workload placement
- Benchmarking against existing tools (iBench, Bubble-Up, Mage, TRACON)

**Why This Research Path:** The combination of graduate research in systems performance with daily production work at Dell Innovation Center creates a unique feedback loop. Theoretical insights from profiling research inform how I approach infrastructure optimization, while production challenges reveal gaps in academic tools. By March 2027, I will have both the deep theoretical foundation and extensive practical experience to contribute at senior/specialist level in performance engineering or infrastructure architecture roles.

**Strategic Timeline:**
- **March-April 2026:** Research plan (PeP) submission
- **2026:** Prototype development, comparative benchmarking, scheduler integration
- **March-April 2027:** Thesis defense and graduation

**Connection to Professional Work:** Interference profiling directly parallels my Dell work in database performance benchmarking. Both require systematic measurement methodologies, understanding of system-level interactions, and translating metrics into actionable insights. This research provides the theoretical foundation for problems I am already solving in production.

### IEEE Publication (2023)

**"A Latency, Throughput, and Programmability Perspective of GrPPI for Streaming on Multi-cores"**  
*31st Euromicro International Conference on Parallel, Distributed and Network-Based Processing (PDP)*

Research on parallel processing platform performance characteristics. This work taught me systematic performance evaluation methodologies that I apply daily in production systems.

[Read the paper](https://doi.org/10.1109/PDP59025.2023.00033)

---

## Selected Projects

### IntP: Container Interference Profiler | PPGCC-PUCRS (2026-2027)
**Role:** Graduate Researcher

Kernel-level profiling tool for measuring performance interference in containerized environments.

**Research Challenges:**
- Adapting SystemTap-based profiling for Linux kernel 6.8.0+ compatibility
- Evaluating eBPF as modern alternative with better container awareness and forward compatibility
- Measuring seven key interference metrics: network physical/stack, block I/O, memory bandwidth, LLC miss ratio, LLC occupancy, CPU utilization
- Integration with container scheduling systems for interference-aware workload placement

**Technical Implementation:**
- SystemTap module loading fixes for modern kernel API changes
- resctrl-based LLC monitoring architecture
- Comparative benchmarking framework against iBench, Bubble-Up, Mage, TRACON
- Hardware validation across consumer (i7-13650HX) and server (Xeon) platforms

**Research Impact:** Addressing fundamental gap in container performance tooling where existing solutions struggle with kernel compatibility and container-native integration. Work contributes to more efficient resource utilization in multi-tenant containerized systems.

**Stack:** C, SystemTap, eBPF, bpftrace, BCC, libbpf, Linux kernel 6.8.0, Ubuntu 24.04, resctrl, RDT

### Multi-Cloud Hospitality Platform | AGES PUCRS (July 2025 - Present)
**Role:** Project Manager & Infrastructure Architect

Leading infrastructure for digital reservation system serving ecological research center.

**Architecture Highlights:**
- Multi-cloud design with AWS as primary and Azure for disaster recovery
- Zero-downtime deployments through GitLab CI/CD
- PostgreSQL master-slave replication with automated failover
- Complete observability with Grafana, Prometheus, Umami, Metabase

**Team Leadership:** Managed cross-functional team of 8+ developers, coordinating backend, frontend, and infrastructure work streams.

**Stack:** NestJS, TypeScript, PostgreSQL, Docker Swarm, Terraform, Ansible, AWS, Azure, GitLab CI/CD

### Intelligent Manufacturing Platform | AGES PUCRS (Aug-Dec 2024)
**Role:** Software Architect & Infrastructure Tech Lead

Backend architecture and infrastructure for production line management system.

**Technical Decisions:**
- NestJS/TypeScript backend following Clean Architecture for maintainability
- PostgreSQL replication strategy for high availability requirements
- AWS EC2 load balancing for traffic distribution
- Ansible automation for consistent environment provisioning

**Stack:** NestJS, TypeScript, PostgreSQL, Docker Swarm, Ansible, AWS EC2, GitLab CI/CD

### Parallel Processing Research | GMAP-PUCRS (Nov 2020 - Oct 2022)
**Role:** Scientific Research Scholar

Research in parallel stream processing resulting in IEEE publication.

**Research Contributions:**
- Performance analysis of parallel processing platform across multiple architectures
- Benchmarking methodology design for latency and throughput evaluation
- Implementation of parallel applications using C++, Intel TBB, and native threads

**Stack:** C++, Intel TBB, C++ Native Threads, Benchmarking Tools

---

## Technical Stack

**Languages:** Go, Python, C++, C, TypeScript, Shell Script  
**DevOps & IaC:** Terraform, Ansible, Docker, Kubernetes, Podman, GitLab CI/CD, GitHub Actions  
**Backend:** NestJS, Node.js, Express, RESTful APIs, gRPC  
**Databases:** PostgreSQL, MongoDB, Oracle, Prisma, Sequelize  
**Performance & Profiling:** HammerDB, YCSB, Prometheus, Grafana, SystemTap, eBPF, bpftrace, BCC, libbpf  
**Cloud:** AWS (EC2, S3), Azure  
**Systems Programming:** Linux Kernel Instrumentation, resctrl, RDT, perf  
**Parallel Processing:** Intel TBB, OpenMP, C++ Threading

---

## Education & Certifications

**M.Sc. Computer Science** | PPGCC-PUCRS | 2026-2027 (accelerated track)  
Integra-Pós G+1 Program - Core coursework completed during undergraduate studies  
Focus: Systems Performance and Container Interference Profiling  
Advisor: Prof. Cesar Augusto Fonticielha De Rose

**B.Sc. Software Engineering** | PUCRS | 2020-2026  
Graduated: January 9, 2026  
Selected for Integra-Pós G+1 accelerated Master's program based on IEEE publication

**Multicloud DevOps & AI Challenge** | The Cloud Bootcamp | 2025

---

## Languages

**Portuguese:** Native  
**English:** Full Professional Proficiency

---

## GitHub Activity

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com/?user=Saccilotto&theme=vue-dark&hide_border=false)](https://git.io/streak-stats)

</div>

<details>
<summary>View More GitHub Stats</summary>

<div align="center">

![Stats](https://github-readme-stats-git-masterrstaa-rickstaa.vercel.app/api?username=Saccilotto&theme=vue-dark&show_icons=true&hide_border=false&count_private=true)

![Top Languages](https://github-readme-stats-git-masterrstaa-rickstaa.vercel.app/api/top-langs/?username=Saccilotto&theme=vue-dark&show_icons=true&hide_border=false&layout=compact)

</div>

</details>

---

## Contact & Links

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/saccilotto)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sacilotto.andre@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Saccilotto)
[![IEEE](https://img.shields.io/badge/IEEE-00629B?style=for-the-badge&logo=ieee&logoColor=white)](https://doi.org/10.1109/PDP59025.2023.00033)

---

## Professional Philosophy

I believe the best engineers combine theoretical understanding with practical experience. My approach integrates academic rigor in problem-solving with hands-on production engineering. This means I do not just implement solutions; I design experiments, measure outcomes, and optimize based on data.

Whether building automation platforms, optimizing database workloads, or developing kernel-level profiling tools, I bring the same systematic methodology: understand the problem deeply, design measurable experiments, iterate based on evidence. My graduate research in systems performance directly informs how I approach production problems, while production challenges reveal gaps in academic tools and motivate better research questions.

The Integra-Pós G+1 program exemplifies my approach to career development: strategic planning to maximize learning velocity while minimizing time-to-impact. By completing graduate coursework during my undergraduate degree and maintaining concurrent industry experience, I am building a foundation that typically requires 5-7 years of separate academic and professional development.

**Current Status:** Actively building production infrastructure at Dell Innovation Center while conducting graduate research in systems performance. Target graduation March 2027 with both M.Sc. degree and extensive production engineering experience. Open to senior-level Backend Engineering, DevOps Engineering, Platform Engineering, Performance Engineering, or Systems Engineering roles where deep technical expertise, research background, and proven production experience provide unique value.

---

*Last Updated: February 2026*
