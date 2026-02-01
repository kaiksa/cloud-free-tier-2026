# Cloud Service Providers Free Tier Comparison 2026

Comparing the free tier offers of major cloud providers. Updated for February 2026.

**🌐 Live Demo:** https://cloud-free-tier-2026.vercel.app

**Star ⭐ this repository if you found it useful!**

## Table of Contents

- [Major Cloud Providers](#major-cloud-providers)
  - [AWS](#1-aws)
  - [Azure](#2-azure)
  - [Google Cloud](#3-google-cloud)
  - [Oracle Cloud](#4-oracle-cloud)
- [Asian Cloud Providers](#asian-cloud-providers)
  - [Alibaba Cloud](#5-alibaba-cloud)
  - [Tencent Cloud](#6-tencent-cloud)
- [Developer-Focused Platforms](#developer-focused-platforms)
  - [DigitalOcean](#7-digitalocean)
  - [Hetzner Cloud](#8-hetzner-cloud)
  - [Linode](#9-linode)
  - [OVHcloud](#10-ovhcloud)
- [Serverless & PaaS](#serverless--paas)
  - [Vercel](#11-vercel)
  - [Netlify](#12-netlify)
  - [Render](#13-render)
  - [Cloudflare](#14-cloudflare)
- [Specialized Services](#specialized-services)
  - [IBM Cloud](#15-ibm-cloud)
  - [Salesforce](#16-salesforce)
  - [JFrog](#17-jfrog)
  - [OpenShift](#18-openshift)
  - [Zeabur](#19-zeabur)

---

## Major Cloud Providers

## 1. AWS

**Homepage:** [AWS Free Tier](https://aws.amazon.com/free/)

### Always Free

**Compute:**
- **EC2:** 750 hours/month of t2.micro or t3.micro (1 vCPU, 1 GB RAM) instances
- **Lambda:** 1M requests/month and up to 3.2M seconds of compute time/month
- **ECS Fargate:** 500 hours/month for 1 vCPU and 1 GB RAM

**Storage:**
- **S3:** 5 GB standard storage, 2,000 PUT requests, 20,000 GET requests/month
- **EBS:** 8 GB of General Purpose SSD (gp2) or 10 GB of Magnetic storage
- **EFS:** 5 GB of Standard One Zone storage

**Database:**
- **DynamoDB:** 25 GB storage, 25 WCUs, 25 RCUs (or 200 RCUs if not using WCUs)
- **RDS:** 750 hours/month of db.t2.micro or db.t3.micro (20 GB storage)
- **ElastiCache:** 750 hours/month of cache.t2.micro or cache.t3.micro

**Network & CDN:**
- **CloudFront:** 1 TB data transfer/month
- **API Gateway:** 1M API calls/month

**Messaging:**
- **SNS:** 1M publishes/month
- **SQS:** 1M requests/month

**Analytics:**
- **CloudWatch:** 10 custom metrics, 10 alarms, 5 GB log ingestion
- **X-Ray:** 100K traced requests/month

### Free Trial (12 Months)
- 5 GB of S3 storage, 2000 GET requests, 20000 PUT requests
- 25 GB of DynamoDB storage
- 750 hours of EC2 t2.micro or t3.micro

---

## 2. Azure

**Homepage:** [Azure Free Account](https://azure.microsoft.com/en-us/free/)

### Free Trial (First 12 Months)
- **$200 credit** for first 30 days
- 12 months of popular free services

**Compute (12 months):**
- **App Service:** 750 hours/month of B1 instances (1 vCPU, 1.75 GB RAM)
- **Functions:** 1M requests/month
- **Container Instances:** 180 vCPU seconds/month

**Database (12 months):**
- **SQL Database:** 4 TB of storage (5 DTU, Basic tier) - 12 months
- **Cosmos DB:** 5 GB provisioned throughput (400 RU/s)
- **Redis Cache:** 250 MB cache

### Always Free

**Compute:**
- **Virtual Machines:** 12 months of free B1S burstable virtual machine (1 vCPU, 1 GB RAM)
- **Functions:** 1M requests/month (continues after 12 months)

**Storage:**
- **Blob Storage:** 100 GB LRS (Locally Redundant Storage)
- **File Storage:** 5 GB LRS file share

**Database:**
- **Cosmos DB:** 5 GB storage with 400 RU/s throughput

**Network:**
- **Bandwidth:** 100 GB of data egress/month

**Analytics:**
- **Application Insights:** 5 GB telemetry data/month
- **Log Analytics:** 5 GB data ingestion/month

---

## 3. Google Cloud

**Homepage:** [Google Cloud Free Tier](https://cloud.google.com/free/docs/gcp-free-tier)

### Always Free

**Compute:**
- **Compute Engine:** e2-micro instance (0.25 vCPU, 1 GB RAM) in us-west1, us-central1, us-east1 regions
  - 30 GB-months of standard persistent disk
  - 200 GB-months of standard persistent disk in standard tier network
  - 1 GB network egress in premium tier (excluding China and Australia)
  - 200 GB network egress in standard tier
- **Cloud Run:** 2M requests/month (US regions only)
- **Cloud Functions:** 2M invocations/month
- **Cloud Build:** 120 minutes/day of build time
- **Artifact Registry:** 50 GB-months storage

**Storage:**
- **Cloud Storage:** 5 GB-months regional storage (US regions only)
- **Filestore:** 1 GB standard tier

**Database:**
- **Cloud SQL:** One Cloud SQL instance (db-f1-micro, 0.6 GB RAM)
- **Firestore:** 1 GB storage, 50K reads, 20K writes/day
- **BigQuery:** 1 TB of querying/month, 10 GB storage/month
- **Spanner:** 10 GB storage/month

**Network:**
- 1 GB network egress/month in premium tier
  - China and Australia excluded
- 200 GB network egress/month in standard tier

**Analytics:**
- **Cloud Monitoring:** 5 GB/month metrics ingestion
- **Cloud Logging:** 50 GB logs retention

### Free Trial ($300 Credit)
- $300 credit for 90 days

---

## 4. Oracle Cloud

**Homepage:** [Oracle Cloud Free Tier](https://www.oracle.com/cloud/free/)

### Always Free

**Compute:**
- **VMs:** 2 AMD-based VM.Standard.E2.1.Micro (1/8 OCPU = 0.25 vCPU, 1 GB RAM) each
- **Arm-based VMs:** 4 VM.Standard.A1.Flex with up to 24 GB RAM total
  - 3,000 OCPU-hours/month and 18,000 GB-memory-hours/month
- **Compute capacity:** Up to 4 OCPUs total across all VMs

**Storage:**
- **Block Volumes:** 200 GB total (2 volumes of 100 GB each)
- **Object Storage:** 10 GB each of Standard, Infrequent Access, and Archive storage tiers

**Database:**
- **Autonomous Database:** 2 databases (20 GB storage each)
  - Includes Oracle Application Express (APEX)
  - Oracle SQL Developer
  - 1 OCPU compute for transaction processing or data warehouse
- **NoSQL Database:** 25 GB storage per table, up to 3 tables

**Network:**
- 10 TB of network egress/month per region (20 TB with dual-region setup)
- **Load Balancers:** 4 total (1 Flexible 10 Mbps, 3 Network)
- **OCI Bastions:** 5 bastions

**Management:**
- **Resource Manager:** Managed Terraform (unlimited stacks)
- **Monitoring & Notifications:** Comprehensive monitoring and alerting
- **Identity & Access:** Full IAM features
- **Audit:** 10 GB of audit logs

### Free Trial (30 Days)
- **$300 credit** for 30 days
- Up to 8 instances across all available services
- Up to 5 TB of storage

**Note:** 1 Oracle OCPU = 2 vCPUs (physical cores with hyperthreading)

---

## Asian Cloud Providers

## 5. Alibaba Cloud

**Homepage:** [Alibaba Cloud Free Trial](https://www.alibabacloud.com/campaign/free-trial)

### Free Trial
- **Free credits** worth $450-$1,300 USD
- **12 months usage** for Elastic Compute Service (ECS)
- Over 40 products available for free trial

**Services included:**
- ECS instances
- OSS storage
- RDS databases
- CDN services
- Load balancing

### Always Free
- Limited always-free tier available for some services

---

## 6. Tencent Cloud

**Homepage:** [Tencent Cloud Free Tier](https://www.tencentcloud.com/campaign/freetier)

### Always Free
- **Elastic Network Interface (ENI)**
- **Virtual Private Cloud (VPC)**
- **Auto Scaling (AS)**
- **VPN connections**

### Free Trial
- **$300 credit** for 30-day trial

**Server Locations:**
Shanghai, Nanjing, Guangzhou, Beijing, Chengdu, Chongqing, Hong Kong, Seoul, Tokyo, Singapore, Bangkok, Jakarta, Silicon Valley, Frankfurt, Mumbai, Virginia, São Paulo, Toronto

---

## Developer-Focused Platforms

## 7. DigitalOcean

**Homepage:** [DigitalOcean](https://www.digitalocean.com/)

### Free Trial
- **$100 credit** for 60 days via [do.co/hf100](https://do.co/hf100)

### Pricing (no always-free tier)
- Basic droplets start at $4/month
- App Platform has free tier for static sites

---

## 8. Hetzner Cloud

**Homepage:** [Hetzner Cloud](https://hetzner.cloud)

### Free Trial
- Occasionally offers free credits for new users
- No permanent free tier

### Pricing
- CX11 server: €3.59/month (1 vCPU, 2 GB RAM, 20 GB disk)
- Very competitive pricing for European hosting

---

## 9. Linode

**Homepage:** [Linode](https://www.linode.com)

### Free Trial
- **$100 credit** for 60-day free trial (requires credit card)
- Via [linode.com/lp/free-credit-100](https://www.linode.com/lp/free-credit-100)

### Pricing
- Nanode: $5/month (1 vCPU, 1 GB RAM, 25 GB SSD)
- No always-free tier

---

## 10. OVHcloud

**Homepage:** [OVHcloud](https://www.ovhcloud.com)

### Free Trial
- **€200 credit** for 30 days on all public cloud resources

### Always Free
- **MongoDB:** 512 MB with replication

### Pricing
- Public Cloud instances start at low competitive rates
- Strong European presence with multiple data centers

---

## Serverless & PaaS

## 11. Vercel

**Homepage:** [Vercel](https://vercel.com/pricing)

### Always Free (Hobby Plan)
- **Unlimited deployments** for personal projects
- **35+ frameworks** supported (Next.js, React, etc.)
- **Edge Network:** Global CDN
- **Automatic CI/CD:** Git integration
- **Functions:** Serverless and Edge functions
  - 100 GB bandwidth/month
  - 100 GB hours of serverless function execution
  - 6,000 minutes of Edge Function execution
- **Databases:**
  - 1 Postgres database (256 MB RAM, 60 hours compute)
  - 1 KV store (256 MB storage, 256 reads/day)
- **Analytics:** Web analytics included
- **Preview deployments:** Unlimited

---

## 12. Netlify

**Homepage:** [Netlify](https://www.netlify.com)

### Always Free (Starter Plan)
- **Static site hosting:** Unlimited sites and bandwidth
- **Serverless functions:** 125K invocations/month
- **Edge functions:** 100K requests/month
- **Build minutes:** 300 minutes/month
- **Forms:** 100 submissions/site/month
- **Users:** Up to 1 team member
- **Deploy previews:** Unlimited

---

## 13. Render

**Homepage:** [Render](https://render.com)

### Always Free
- **Static sites:** Unlimited hosting
- **Web services:**
  - 750 hours/month (approximately full month)
  - 0.1 vCPU, 512 MB RAM
  - 100 GB bandwidth
- **Redis:** Free tier available
- **PostgreSQL:** Free tier available (90 days, limited)

**Note:** Free services spin down after 15 minutes of inactivity

---

## 14. Cloudflare

**Homepage:** [Cloudflare](https://www.cloudflare.com/plans/)

### Always Free (Workers Plan)
- **Workers:** 100K requests/day
- **KV Storage:** 1 GB storage, 100K reads/day
- **D1 Database:** 5 GB storage
- **R2 Object Storage:** 10 GB (S3-compatible)
- **Pages:** Unlimited static sites
- **DNS:** Free DNS management
- **CDN:** Unlimited CDN bandwidth
- **SSL:** Free SSL certificates
- **DDoS Protection:** Included
- **WAF:** Basic Web Application Firewall
- **Email Routing:** Free email forwarding

---

## Specialized Services

## 15. IBM Cloud

**Homepage:** [IBM Cloud](https://www.ibm.com/cloud/free)

### Free Trial
- **$200 credit** for 30 days

### Lite Plans (Always Free)
- **Cloud Foundry:** 256 MB RAM
- **Databases:** Various lite plans available
- **Kubernetes:** Lite cluster available
- **Functions:** 400K GB-seconds/month

---

## 16. Salesforce

**Homepage:** [Salesforce Developer Account](https://developer.salesforce.com/signup)

### Free Tier (Developer Account)
- **Lifetime free** developer environment
- Full Salesforce platform access
- Limited storage and API calls

### Free Trial
- 30-day trial with full features

---

## 17. JFrog

**Homepage:** [JFrog Platform](https://jfrog.com/platform/free-trial/)

### Always Free
- **2 GB storage**
- **10 GB transfer/month**
- **2,000 CI/CD minutes/month**

### Free Trial
- 30-day self-hosted trial

---

## 18. OpenShift

**Homepage:** [Red Hat OpenShift](https://www.openshift.com/try)

### Free Trial
- **Try OpenShift 4 cluster** for free
- Interactive Learning Portal available

### Developer Sandbox
- Free developer sandbox environment
- Limited resources, great for learning

---

## 19. Zeabur

**Homepage:** [Zeabur](https://zeabur.com/pricing)

### Always Free
- **Serverless functions and static sites**
- **10 GB outbound data transfer/month**

### Developer Plan
- **100 GB outbound data transfer/month**
- **$5 usage fee/month** (waived for smaller deployments)

---

## Quick Comparison Table

| Provider | Always Free Compute | Free Trial | Storage Free Tier | Network Egress |
|----------|-------------------|------------|------------------|----------------|
| **AWS** | 750h t2.micro | 12 months | 5 GB S3, 8 GB EBS | 1 TB CloudFront |
| **Azure** | 12 months B1S | $200/30d + 12mo | 100 GB Blob | 100 GB/month |
| **GCP** | e2-micro (limited regions) | $300/90d | 5 GB Cloud Storage | 1 GB premium, 200 GB standard |
| **Oracle** | 4 Arm VMs (24 GB RAM) | $300/30d | 200 GB Block, 30 GB Object | 10 TB/month |
| **Vercel** | 100K serverless calls | None | 256 MB Postgres, 256 MB KV | 100 GB/month |
| **Netlify** | 125K functions/month | None | None (static) | Unlimited (static) |
| **Cloudflare** | 100K Workers/day | None | 10 GB R2, 5 GB D1 | Unlimited (CDN) |

---

## Best For...

### **Best Overall Free Tier**
🏆 **Oracle Cloud** - Most generous always-free offering with 4 Arm VMs (24 GB RAM total), 200 GB block storage, and 10 TB egress

### **Best for Serverless**
🏆 **Vercel** - Excellent developer experience, 100K serverless function calls/month, integrated databases

### **Best for Static Sites**
🏆 **Cloudflare** - Unlimited CDN bandwidth, 10 GB R2 storage, Workers, D1 database

### **Best for Learning**
🏆 **Google Cloud** - e2-micro instance, generous free tier on many services, great documentation

### **Best for Enterprises**
🏆 **AWS** - 12-month free tier with t2.micro, extensive service coverage

### **Best for Global Edge**
🏆 **Cloudflare** - Global edge network, unlimited bandwidth, Workers everywhere

---

## Notes

- **Data egress** is often the hidden cost - Oracle Cloud stands out with 10 TB/month free
- **VM specifications** vary significantly across providers
- **Regional restrictions** apply to many free tiers (especially GCP)
- **"Always Free" vs "Free Trial"** - Always Free continues indefinitely, trials expire
- **Credit card required** for most trials, but some always-free tiers don't need it

---

## Contributing

Found outdated information? Submit a PR or open an issue!

Last updated: February 2026

---

**License:** CC0 1.0 Universal (Public Domain)
