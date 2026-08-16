# Client Cloud Recommendations

## Client Scenarios

### Client A – Startup Company
- **Recommended Platform:** AWS
- **Justification:** AWS offers flexible pay-as-you-go tiers and broad community documentation that allow early-stage teams to build and scale without high upfront costs.
- **Three Services Used:** Amazon EC2, Amazon S3, Amazon RDS.

### Client B – University
- **Recommended Platform:** Microsoft Azure
- **Justification:** Universities usually operate on existing Microsoft domain software, allowing Azure to seamlessly handle identity controls through Active Directory.
- **Three Services Used:** Microsoft Entra ID, Azure VMs, Azure SQL Database.

### Client C – AI Research Company
- **Recommended Platform:** Google Cloud Platform (GCP)
- **Justification:** GCP offers specialized Tensor Processing Units (TPUs) and optimized deep-learning pipelines designed specifically for complex machine learning tasks.
- **Three Services Used:** Compute Engine, Vertex AI, Google Cloud Storage.

### Client D – Global E-Commerce Company
- **Recommended Platform:** AWS
- **Justification:** AWS has global region distribution and scalable infrastructure designed to maintain continuous uptime during traffic spikes.
- **Three Services Used:** Amazon EC2, Amazon Route 53, Amazon CloudFront.

---

## Multi-Cloud Decision Matrix

| Business Requirement | Recommended Platform | Justification |
| :--- | :--- | :--- |
| **Startup Company** | AWS | Low starter costs, large developer community, and rapid deployment tools. |
| **Enterprise Organization** | AWS / Azure | Enterprise-grade security compliance, hybrid deployment support, and dedicated support. |
| **Microsoft Environment** | Microsoft Azure | Native compatibility with Microsoft Active Directory and Windows Server ecosystems. |
| **AI / Machine Learning** | GCP | Native integration with TPUs, BigQuery data engines, and Vertex AI. |
| **Kubernetes Deployment** | GCP | Industry-leading managed GKE platform built by the originators of Kubernetes. |
| **Global Web Application** | AWS | Global network distribution with low-latency edge node caching via CloudFront. |
