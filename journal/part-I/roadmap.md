# 📖 Roadmap — Part 1: Host My First Doc Site

Prelude to the 6 Sections:
The **documentation site itself is not important**.  
What matters is the **way we build and host it**: reproducible, portable deployments that work across multiple platforms.  
Why? Because the same approach we use here can be applied again and again — not only for a website, but for any service we want to self-host later (password manager, personal cloud, media server, etc.).
That’s why my focus is on reproducible deployment:

---

## ✅ Guiding Principles
- Do it once → do it everywhere (cloud, GitHub, Raspberry Pi).  
- Same process, different platforms.  
- The true achievement is the **method**, not just the service.  

---

## Sections & Progress

### ☐ Section 1: Pick & Prepare a Cloud Provider
**Why first?**  
To understand the “terrain” before designing deployments. Each cloud provider has its own rules and limits. 
Before I design how to deploy services, I need to understand the “terrain.” Cloud platforms are not all the same. I must know their differences — CPU, memory, networking rules — so I don’t design something that only works on my laptop but fails in the cloud.

**Learning Outcomes:**  
- How to register a cloud service and create a VM.  
- What a virtual machine is and how it behaves.  
- Basic setup: SSH access, open ports, updates.  

The idea that “cloud” is just someone else’s computer, but with its own rules.

---

### ☐ Section 2: Docker + Compose for Build & Serve
**Why second?**  
Now that I know what the cloud looks like, I can design the “toolbox” that will run my services the same way everywhere. Docker + Compose will be the foundation of portability.

**Learning Outcomes:**  
- What containers are and why they are just portable boxes that run the same code everywhere.
- How to write a simple recipe (Compose file) to build and serve the site.  
- Why the same approach can scale beyond websites.  

---

### ☐ Section 3: Deploy on Cloud
**Why third?**  
Turn theory into practice with the first public win: running a service in the cloud.  

**Learning Outcomes:**  
- How to take the same recipe and run it remotely on cloud machine.  
- How to expose a service to the internet, open it to the world (so friends or recruiters can visit).
- The feeling of creating something real and visible.  

---

### ☐ Section 4: Mirror to GitHub Pages
**Why fourth?**  
Cloud servers can break, accounts can expire. A mirror on GitHub ensures the site is always visible even if my experiments fail. It’s a safety net.

**Learning Outcomes:**  
- Why redundancy is essential. Don’t rely on a single provider.
- How automation keeps a site alive even if servers fail.  
- The role of backups and mirrors in self-hosting.  

---

### ☐ Section 5: Self-Host on Raspberry Pi
**Why fifth?**  
The heart of the journey: **taking control** by hosting the service at home. 
Instead of running on someone else’s computer, I run the same service on my own Raspberry Pi at home. This is where self-hosting truly begins.

**Learning Outcomes:**  
- How a small, affordable device can act as a real server.
- How to migrate from cloud to home using the **exact** same recipe.
- The taste of **independence**: the service lives in my house, under my control.

---

### ☐ Section 6: Parity & Verification Across Platforms
**Why last?**  
To prove reproducibility. The method must work the same everywhere.  

**Learning Outcomes:**  
- How to check that all deployments match (cloud, GitHub, Pi).  
- The discipline of verification and documentation.  
- Why reproducibility is more valuable than the site itself.  

---

## 📌 End of Part 1
By completing these 6 sections:  
- The doc site will exist on multiple platforms.  
- The real achievement will be a **repeatable, portable method**.  
- This method becomes the foundation for self-hosting future services.
