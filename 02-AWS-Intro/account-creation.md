# ☁️ Cloud Free Tier Comparison (AWS vs Azure vs GCP)

> Updated: August 2025  
> A quick reference on how the free tiers work across the 3 big cloud providers.

---

## 🔑 Overview

When starting with cloud platforms, each provider offers a "Free Tier" or "Free Plan."  
But the **duration, credits, and included services** differ between **AWS, Azure, and Google Cloud Platform (GCP)**.

This guide compares them side-by-side.

---

## 🟠 AWS Free Plan (New Rules in 2025)

- **Accounts before July 15, 2025:**  
  - ✅ **12-month Free Tier** + Always-Free services.  
  - ⚠️ After 12 months → pay-as-you-go billing.  

- **Accounts created on/after July 15, 2025:**  
  - ✅ **6 months Free Plan** OR until credits are used.  
  - 🎁 **$100 signup credits** + **up to $100 earned credits** (completing tasks).  
  - ⏳ After expiry → account closed, 90-day data retention.  

**Always Free Examples (with usage limits):**  
- Lambda (1M requests/month)  
- DynamoDB (25 GB storage)  
- S3 (5 GB storage)

**Outcome:** Great for beginners & labs, but stricter than before.

---

## 🔵 Microsoft Azure Free Tier

- ✅ **12 months Free** of popular services.  
- 🎁 **$200 credit** valid for **30 days** at signup.  
- ⏳ After 12 months → convert to Pay-As-You-Go (or account disabled).  
- **Always Free** services available (e.g., 750 hours B1S VM, 5 GB Blob Storage).  

**Examples:**  
- 750 hours of Linux/Windows VM (B1S) for 12 months.  
- 5 GB Azure Blob Storage (Always Free).  
- Azure Functions: 1M requests/month (Always Free).

**Outcome:** Best for testing Windows workloads & .NET integrations.

---

## 🟢 Google Cloud Platform (GCP) Free Tier

- ✅ **$300 credit** valid for **90 days** at signup.  
- ✅ **Always Free Tier** with usage limits.  
- ⏳ After credit expiry → pay-as-you-go.  

**Always Free Examples (with regional limits):**  
- 1 f1-micro VM per month (US regions only).  
- 5 GB storage on Google Cloud Storage.  
- 2M Cloud Functions invocations/month.  
- 1 GB of BigQuery storage + 1 TB queries/month.

**Outcome:** Best for experimenting with serverless, ML, and data analytics.

---

## 📊 Quick Comparison Table

| Feature                | **AWS** (Post-2025)                 | **Azure**                         | **GCP**                             |
|-------------------------|-------------------------------------|-----------------------------------|--------------------------------------|
| **Initial Credit**      | $100 (+$100 earned tasks)           | $200 (30 days)                    | $300 (90 days)                       |
| **Duration**            | 6 months (new) / 12 months (legacy) | 12 months + 30-day credit         | 90 days credit + Always Free         |
| **Always Free**         | Yes (Lambda, S3, DynamoDB, etc.)    | Yes (VMs, Blob Storage, Functions)| Yes (VM, Cloud Storage, Functions)   |
| **Post Expiry**         | Account closed unless upgraded      | Must upgrade → Pay-As-You-Go      | Must upgrade → Pay-As-You-Go         |
| **Best Use Case**       | Beginner AWS labs & infra basics    | Windows/.NET workloads            | Serverless, ML, Big Data             |

---

## 🎯 Key Takeaways

- **AWS**: Now stricter → only **6 months for new accounts**, but offers task-based credits.  
- **Azure**: Best if you want Windows or hybrid cloud workloads.  
- **GCP**: Very generous “Always Free” services (great for data/ML).  

---

## 📌 References

- [AWS Free Tier Update 2025](https://aws.amazon.com/blogs/aws/aws-free-tier-update-new-customers-can-get-started-and-explore-aws-with-up-to-200-in-credits/)  
- [Azure Free Account](https://azure.microsoft.com/en-us/free)  
- [Google Cloud Free Tier](https://cloud.google.com/free)  

---
