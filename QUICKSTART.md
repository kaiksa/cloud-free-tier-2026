# Quick Reference Guide

## 🏆 Top Picks by Category

### **Best Overall Value: Oracle Cloud**
- 4 Arm-based VMs (24 GB RAM total)
- 200 GB block storage
- 10 TB network egress/month
- 2 Autonomous Databases (20 GB each)
- **No credit card required for always-free tier**

### **Best for Frontend Developers: Vercel**
- 100K serverless function calls/month
- Integrated Postgres and KV storage
- Next.js optimized
- Global edge network
- Unlimited deployments

### **Best for Static Sites: Cloudflare**
- Unlimited CDN bandwidth
- Workers (100K requests/day)
- R2 object storage (10 GB, S3-compatible)
- D1 SQL database (5 GB)
- Pages for static sites

### **Best for Learning: Google Cloud**
- Free e2-micro instance (limited regions)
- Extensive free tier across services
- Excellent documentation
- Interactive tutorials available

### **Best for Enterprise: AWS**
- 12-month free tier
- Broadest service coverage
- Industry standard
- Strong ecosystem

---

## 💡 Tips to Maximize Free Tiers

### **Avoid Unexpected Costs:**
1. **Set budget alerts** - All major clouds have free budget alerting
2. **Monitor data egress** - This is the most common unexpected cost
3. **Watch regional pricing** - Some regions don't qualify for free tier
4. **Clean up resources** - Delete unused instances and storage
5. **Use reserved capacity** - Some providers offer better deals for reservations

### **Best Practices:**
- **Read the fine print** - Always-free tiers often have limitations
- **Check regional availability** - Some services are region-specific
- **Monitor usage** - Set up alerts before you hit limits
- **Use multiple providers** - Spread services across providers for redundancy
- **Document your setup** - Keep track of what you're using

### **Hidden Costs to Watch:**
- **Data transfer** between regions
- **IP addresses** (sometimes charged separately)
- **Load balancers** (often not included in free tier)
- **Support tickets** (paid support only for free tiers)
- **Storage beyond free limits**

---

## 🚀 Quick Start: Which Should You Choose?

### **For Personal Projects:**
- **Frontend/Static Sites:** Vercel, Netlify, or Cloudflare Pages
- **Full-Stack Apps:** Oracle Cloud (always-free VMs)
- **Serverless:** Vercel or Cloudflare Workers
- **Databases:** Oracle Cloud or Supabase (not listed, but good)

### **For Learning:**
- **General Cloud Skills:** Google Cloud or AWS
- **Kubernetes:** Oracle Cloud (always-free) or OpenShift
- **Serverless:** Cloudflare Workers or Vercel
- **DevOps:** Oracle Cloud + Terraform

### **For Startups:**
- **MVP:** Oracle Cloud (most generous always-free)
- **Frontend-First:** Vercel + Cloudflare
- **Global Reach:** Cloudflare + Oracle Cloud
- **Cost Optimization:** Mix multiple providers

### **For Enterprise:**
- **AWS or Azure** for production
- **Use free tiers** for development/testing
- **Multi-cloud strategy** for redundancy

---

## 📊 Free Tier Expiration Dates

### **No Expiration (Always Free):**
- Oracle Cloud (always-free tier)
- Cloudflare
- Vercel (Hobby plan)
- Netlify (Starter plan)
- Render (free tiers)

### **12 Months:**
- AWS (limited services)
- Azure (limited services)

### **30-90 Days Trial:**
- AWS ($300 credit - 90 days, actually)
- Azure ($200 credit - 30 days)
- Google Cloud ($300 credit - 90 days)
- Oracle Cloud ($300 credit - 30 days)
- DigitalOcean ($100 - 60 days)
- Linode ($100 - 60 days)

---

## 🔄 Migration Tips

### **Easy to Migrate:**
- **Static sites** - Just point DNS elsewhere
- **Container images** - Docker is portable
- **Serverless functions** - Code is portable, platform isn't

### **Harder to Migrate:**
- **Databases** - Requires export/import, downtime
- **Managed services** - Often provider-specific
- **CDN configurations** - Complex setups

### **Best Practice:**
- **Use Terraform** - Infrastructure as code makes migration easier
- **Avoid vendor lock-in** - Use standard APIs where possible
- **Keep regular backups** - Especially databases
- **Test migrations** - Don't wait until you need to migrate

---

## 📚 Recommended Learning Path

1. **Start with Vercel or Netlify** - Deploy your first project
2. **Try Oracle Cloud always-free** - Get VM experience
3. **Experiment with Cloudflare Workers** - Learn serverless
4. **Build something on AWS or GCP** - Learn major cloud provider
5. **Use Terraform** - Learn infrastructure as code
6. **Set up monitoring** - Learn to track costs and performance

---

## 🔗 Useful Tools

- **Terraform** - Infrastructure as code across providers
- **Kubernetes** - Container orchestration (Oracle Cloud free)
- **Docker** - Container images for portability
- **GitHub/GitLab** - CI/CD across all providers
- **Prometheus/Grafana** - Monitoring and alerting

---

*Last updated: February 2026*
