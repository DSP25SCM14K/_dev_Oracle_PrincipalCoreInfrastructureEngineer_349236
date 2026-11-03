# Oracle requisition 349236 — role and company research

Research date: November 3, 2026

## The role in the posting

Oracle’s current posting is **Principal Core Infrastructure Engineer**, requisition **349236**, a U.S.-based individual-contributor role posted October 29, 2026. The listing says 6–10+ years of experience and describes a customer-facing AI/ML infrastructure assignment: participate in pre-sales discovery, design and maintain infrastructure for customer AI/ML initiatives, collaborate with customer data science, software, and Infra/IT teams as well as sales and internal cloud teams, and troubleshoot proof-of-concept and production deployments. Its stated engineering outcomes are efficient, secure, scalable deployment with strong performance, reliability, and cost effectiveness.

The description’s opening sentence calls the position “Senior Core Infrastructure Engineer,” while the page title says “Principal Core Infrastructure Engineer.” The report follows the page title and flags the wording difference rather than silently resolving it.

## What the work likely involves

Based on the posting and Oracle’s public technical materials, this is a blend of infrastructure engineering and customer solution delivery. The engineer is expected to move between discovery, architecture, hands-on implementation, performance diagnosis, and customer production readiness. The technical center is likely to include GPU-backed training or inference, Kubernetes orchestration, distributed storage and networking, security boundaries, observability, scaling, and practical cost controls. The emphasis on troubleshooting both POCs and production points to fast, evidence-led iteration across different customer environments.

This role interpretation is an inference from the duties in the posting and Oracle’s public AI infrastructure documentation; it does not claim access to a private team charter.

## Oracle / OCI context

Oracle Cloud Infrastructure presents AI infrastructure as an integrated path across bare-metal and VM GPU compute, cluster networking, storage, and managed cloud services. Oracle’s current AI infrastructure overview describes GPU clusters, high-bandwidth storage, and RDMA networking as core building blocks for large training and inference workloads. It lists cluster-network latency in the 2.5–9.1 microsecond range and up to 3,200 Gb/sec of cluster-network bandwidth on the page reviewed for this report. These are Oracle-published platform specifications, not claims about the candidate’s systems.

Oracle’s OKE documentation describes support for GPU and high-performance networking nodes, autoscaling, node lifecycle management, cluster healing, IAM/RBAC integration, private clusters, encryption, and workload isolation. Oracle’s AI/LLM reference architecture connects model-development workspaces, production inference, GPU infrastructure, storage, CI/CD, and governance. Oracle also published GPU Cluster Health Checks in October 2026 for evaluating GPU, driver, network, and inter-node communication health before AI/HPC runs, with supported OKE repair signals.

Recent Oracle infrastructure announcements emphasize keeping accelerators productive by coordinating compute, networking, storage, and resilience. For a customer engineer, that translates into making the whole workload path observable and economically viable, not just provisioning GPU instances.

## Resume-to-role fit

The supplied resume provides strong, specific evidence for the posting’s core needs:

- **AI/ML workload operations:** sub-200 ms p95 inference at 5× peak on Kubernetes GPU node pools; inference batching on preemptible capacity; model-serving and RAG project experience.
- **Customer-facing delivery:** 6 of 8 customer POCs converted to production, with discovery and troubleshooting alongside sales, data scientists, and Infra/IT teams.
- **Reliability and diagnosis:** 99.99% availability, multi-region failover, fault injection, brown-out testing, OpenTelemetry, Grafana, runbooks, and 40–45% lower MTTR.
- **Security and isolation:** zero cross-tenant incidents; RBAC, least-privilege IAM, TLS, secrets management, audit logging, and SOC 2 Type II review evidence.
- **Cost and capacity:** 30% lower GPU/compute spend through right-sizing, batching, and preemptible capacity; earlier 30% cloud-cost reduction and 3× processing throughput.
- **Breadth and communication:** Java, Go, Python, and C++; Kubernetes, Terraform, Kafka/Spark, OCI/AWS; proof-of-concept and production collaboration across technical and commercial groups.

The portfolio foregrounds these proof points and frames the candidate’s through-line as taking AI infrastructure from workload discovery to production operation. It retains the full experience bullets from the resume and supplies source links for each listed project. Technical demos appear only for projects with a demo URL supplied by the user.

## Research sources

- [Oracle Careers — requisition 349236](https://careers.oracle.com/en/sites/jobsearch/job/349236/)
- [Oracle AI Infrastructure](https://www.oracle.com/ai-infrastructure/)
- [Oracle Cloud Infrastructure — OKE overview](https://docs.oracle.com/en-us/iaas/Content/ContEng/Concepts/contengoverview.htm)
- [Oracle — secure and scalable self-service AI/LLM reference architecture](https://docs.oracle.com/en/solutions/oci-generative-ai-llm-platforms/index.html)
- [Oracle — GPU Cluster Health Checks release note](https://docs.oracle.com/en-us/iaas/releasenotes/compute/cluster-health-checks.htm)
- [Oracle — deploy an OCI GPU HPC cluster](https://docs.oracle.com/en/learn/oci-gpu-hpc-cluster/index.html)
- [Oracle Cloud Infrastructure — Building the Next Decade of OCI](https://www.oracle.com/news/announcement/blog/ai-world-building-the-next-decade-of-oracle-cloud-infrastructure-2026-10-27/)
