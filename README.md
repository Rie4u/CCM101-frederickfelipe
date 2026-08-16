# CCM101-frederickfelipe
Cloud Computing Coursework and Laboratory Activities

---

## Laboratory 03: Multi-Cloud Explorer

### Project Overview
This laboratory explores core cloud concepts, multi-cloud platforms (AWS, Azure, and GCP), and basic Linux system investigation. The project compares hosting equivalents across major cloud service providers and documents system metrics evaluated inside a live Linux environment.

---

## System Investigation Details

### Terminal Environment Setup & System Inspection
The following standard Linux commands were executed inside the Killercoda Ubuntu environment to evaluate hardware specs and system resources:

| Command | Description / Purpose |
| :--- | :--- |
| `uname -a` | Displays system kernel details, OS version, and machine architecture. |
| `lscpu` | Gathers detailed information about the CPU architecture and core count. |
| `free -h` | Displays total, used, and available system memory (RAM) in human-readable format. |
| `df -h` | Checks file system disk space usage across mounted storage volumes. |
| `adduser <username>` | Creates a new system user account in the Linux environment. |

---

## Cloud Hosting Equivalents

If this local/virtual Linux environment were migrated to the cloud, it could be hosted on the following infrastructure-as-a-service (IaaS) offerings:

* **AWS:** Amazon EC2 (Elastic Compute Cloud)
* **Azure:** Azure Virtual Machines
* **GCP:** Google Compute Engine
