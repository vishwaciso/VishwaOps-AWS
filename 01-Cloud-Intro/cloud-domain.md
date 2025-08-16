# ☁️ Cloud Domains Roadmap with Certifications

## 📌 Introduction
Welcome to the **Cloud Career Roadmap** — a one-stop guide for students, freshers, and professionals transitioning into the cloud industry.  
Cloud is **not** just one technology; it’s a **collection of domains** — each with its own career paths, certifications, and skills.  

This README explains:
- **What to learn before the cloud** in each domain
- **How the same domain works in the cloud**
- **Career path from beginner to expert**
- **Relevant certifications**
- **Real-world examples**

---

## ☁️ Cloud as a Collection of Domains
Cloud is made up of multiple **technology domains** that used to be separate before.  
Now, each of these domains exists **inside the cloud** with additional automation, scalability, and managed services.

| Domain | Before Cloud (On-Prem) | In Cloud |
|--------|------------------------|----------|
| Networking 🌐 | Switches, routers, firewalls | Virtual networks, load balancers, gateways |
| Storage 📦 | NAS, SAN, tapes | S3, Blob Storage, EBS, Cloud Volumes |
| Compute 🖥️ | Physical servers | EC2, Azure VM, GCP Compute Engine |
| OS 🐧🪟 | Bare-metal/Linux/Windows servers | Cloud images, serverless OS layers |
| Middleware 🔄 | WebSphere, Tomcat | Managed middleware services |
| Database 🗄️ | Oracle, MySQL on-prem | RDS, Cloud SQL, Cosmos DB |
| Security 🔒 | Firewalls, IDS/IPS | IAM, WAF, security groups |
| DevOps ⚙️ | Jenkins, GitLab | CI/CD pipelines in the cloud |
| Monitoring 📊 | Nagios, Zabbix | CloudWatch, Azure Monitor |
| Backup & DR 💾 | Tape backups, DR sites | Cloud backup services |
| AI/ML 🤖 | On-prem GPU clusters | SageMaker, Vertex AI |
| FinOps 💰 | IT cost optimization | Cloud cost management |

---

## 🌐 Domain 1: Networking
### **Before Cloud**
- OSI & TCP/IP, IP addressing, VLANs  
- Routing protocols (RIP, OSPF, BGP)  
- Certifications: **CCNA → CCNP → CCIE**  

### **In Cloud**
- VPC, Subnets, Routing tables  
- Security Groups, NACLs  
- Load balancers, VPN gateways  

### **Certifications Mapping**
| Level | Certifications |
|-------|----------------|
| Beginner | AWS Cloud Practitioner, Azure Fundamentals |
| Intermediate | AWS Advanced Networking Specialty |
| Expert | CCIE Enterprise + Cloud Networking |

### **Real-World Scenario**
> A multinational uses **AWS Transit Gateway** to connect 20 VPCs across 3 regions.

---

## 📦 Domain 2: Storage
### **Before Cloud**
- DAS, NAS, SAN  
- RAID levels  
- Certifications: NetApp, Dell EMC  

### **In Cloud**
- **Object**: S3, Blob  
- **Block**: EBS, Azure Disk  
- **File**: EFS, Azure Files  
- Tiered storage  

### **Certifications Mapping**
| Level | Certifications |
|-------|----------------|
| Beginner | AWS S3 Basics |
| Intermediate | AWS Storage Specialty |
| Expert | NetApp Certified Hybrid Cloud Admin |

### **Real-World Scenario**
> A streaming app uses **S3 Standard** for active content and **Glacier** for archive.

---

## 🖥️ Domain 3: Compute
### **Before Cloud**
- Server racks, blade servers  
- Certifications: CompTIA Server+  

### **In Cloud**
- EC2, Azure VM, GCP Compute Engine  
- Auto-scaling groups  
- Serverless (Lambda, Azure Functions)  

### **Certifications Mapping**
| Level | Certifications |
|-------|----------------|
| Beginner | AWS Compute Basics |
| Intermediate | AWS SysOps, Azure Admin |
| Expert | AWS Solutions Architect Pro |

### **Real-World Scenario**
> Black Friday scaling using **EC2 Auto Scaling Groups**.

---

## 🐧🪟 Domain 4: Operating Systems
### **Before Cloud**
- Linux (RHCSA, RHCE)  
- Windows Server (MCSA, MCSE)  

### **In Cloud**
- Marketplace OS images  
- Automated patching  

### **Certifications Mapping**
| Beginner | Linux Essentials, Windows Fundamentals |
| Intermediate | RHCSA, MCSA |
| Expert | RHCE, MCSE Cloud Track |

### **Real-World Scenario**
> Deploy **pre-hardened Ubuntu images** for compliance.

---

## 🔄 Domain 5: Middleware
### **Before Cloud**
- WebSphere, Tomcat, JBoss  
- App server tuning  

### **In Cloud**
- Managed middleware (AWS MQ, Azure Service Bus, GCP Pub/Sub)  

### **Certifications Mapping**
| Beginner | Cloud App Integration Basics |
| Intermediate | Oracle Middleware Cloud Cert |
| Expert | TOGAF + Cloud Integration Tracks |

### **Real-World Scenario**
> Use **Amazon MQ** to integrate microservices.

---

## 🗄️ Domain 6: Databases
### **Before Cloud**
- Oracle, MySQL, MS SQL  
- Backup strategies  

### **In Cloud**
- RDS, DynamoDB, CosmosDB  
- Managed replication, global tables  

### **Certifications Mapping**
| Beginner | AWS RDS Basics |
| Intermediate | AWS Database Specialty |
| Expert | Oracle Certified Cloud DBA |

### **Real-World Scenario**
> Banking app uses **Aurora Global DB** for low-latency multi-region access.

---

## 🔒 Domain 7: Security
### **Before Cloud**
- Firewalls, IDS/IPS  
- PKI, VPNs  

### **In Cloud**
- IAM, MFA, Security Groups  
- WAF, Shield, Key Management  

### **Certifications Mapping**
| Beginner | CompTIA Security+, AWS Cloud Practitioner |
| Intermediate | AWS Security Specialty |
| Expert | CISSP, CCSP |

### **Real-World Scenario**
> Enable **MFA + IAM least privilege** in AWS org.

---

## ⚙️ Domain 8: DevOps
### **Before Cloud**
- Jenkins, GitLab CI  
- Manual deployments  

### **In Cloud**
- AWS CodePipeline, Azure DevOps  
- GitHub Actions, Terraform, Ansible  

### **Certifications Mapping**
| Beginner | Docker + Git Basics |
| Intermediate | AWS DevOps Pro, Azure DevOps Engineer |
| Expert | Kubernetes Admin (CKA) |

### **Real-World Scenario**
> Use **Terraform + CodePipeline** to deploy apps automatically.

---

## 📊 Domain 9: Monitoring
### **Before Cloud**
- Nagios, Zabbix  
- Manual log parsing  

### **In Cloud**
- CloudWatch, Azure Monitor, GCP Operations Suite  
- Logging, Tracing, Metrics  

### **Certifications Mapping**
| Beginner | AWS CloudWatch Basics |
| Intermediate | Datadog, Splunk Certifications |
| Expert | Observability Engineering (New Relic, Elastic) |

### **Real-World Scenario**
> E-commerce site uses **CloudWatch Alarms** to trigger auto-scaling.

---

## 💾 Domain 10: Backup & DR
### **Before Cloud**
- Tape backup, DR site replication  

### **In Cloud**
- S3 Backup, Azure Backup, AWS Backup  
- Cross-region replication  
- DR strategies: Pilot Light, Warm Standby, Hot Site  

### **Certifications Mapping**
| Beginner | AWS Backup Basics |
| Intermediate | AWS Disaster Recovery Specialty |
| Expert | BCDR Specialist |

### **Real-World Scenario**
> Hospital maintains **Pilot Light DR** in another AWS region.

---

## 🤖 Domain 11: AI/ML
### **Before Cloud**
- On-prem GPU clusters  
- Hadoop, Spark  

### **In Cloud**
- AWS SageMaker, Azure ML, GCP Vertex AI  
- Pre-trained AI APIs (Vision, Translate, Speech)  

### **Certifications Mapping**
| Beginner | AI Fundamentals (Azure, AWS) |
| Intermediate | AWS Machine Learning Specialty |
| Expert | TensorFlow Cloud Engineer |

### **Real-World Scenario**
> Retailer predicts demand using **SageMaker ML models**.

---

## 💰 Domain 12: FinOps
### **Before Cloud**
- IT budget planning  
- CapEx vs OpEx  

### **In Cloud**
- Cloud Cost Explorer, Azure Cost Mgmt  
- Rightsizing, Reserved Instances, Spot  

### **Certifications Mapping**
| Beginner | FinOps Foundation Practitioner |
| Intermediate | AWS Cloud Economics |
| Expert | FinOps Certified Professional |

### **Real-World Scenario**
> Company saves **30% costs** by moving to Reserved + Spot instances mix.

---

## 🎯 Learning Strategy
1. Pick a domain of interest.  
2. Learn **Before Cloud** concepts.  
3. Transition to **In Cloud** services.  
4. Earn certifications at each level.  
5. Practice **real-world scenarios**.  

---

## 🗣️ Interview Prep Tips
- Understand **concept + cloud implementation**.  
- Prepare **real project scenarios**.  
- Learn **cross-domain integrations**.  

---
