---
title: Attack and Defend Software Supply Chain (Virtual) - Blackhat Asia 2024

event: BlackHat Asia 2024
event_url: https://www.blackhat.com/asia-24/training/schedule/index.html#attack-and-defend-software-supply-chain-virtual-36009

location: Virtual/Marina Bay Sands, Singapore

address:
  street: Marina Bay Sands
  country: Singapore

summary: Training on different attack & defense strategies for software supply chain security.
abstract: ''

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2024-04-16T13:00:00Z'
date_end: '2024-04-17T15:00:00Z'
all_day: true

# Schedule page publish date (NOT talk date).
publishDate: '2024-03-24T00:00:00Z'

authors: ['Kumar Ashwin', 'Anant Shrivastava']
tags: ['training', 'supplychain', 'security']

# Is this a featured talk? (true/false)
featured: true

image:
  caption: ''
  focal_point: Right

links:
  - icon: twitter
    icon_pack: fab
    name: Follow
    url: https://twitter.com/0xCardinal
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

---
# EXPERIENCE
Virtual

# OVERVIEW
NOTE: This course will be offered virtually via Zoom

In an era where up to 80% of your code can come from third parties, the security of your software supply chain is more critical than ever. Software isn't built in silos anymore. It's built on a complex web of dependencies, with each component sourced from different providers across the globe. This opens up a myriad of vulnerabilities, making your software supply chain a prime target for cybercriminals.



## Day 1:

From the Attacker's Perspective - Understanding Software Supply Chain Attacks

The journey begins by exploring the reality of today's software supply chains, software supply chain is not just your code dependencies there is a whole other set of software's that are part of your supply chain and all need to be protected. We will dissect real-world attacks on software supply chains, understand how they unfolded, and examine their impacts.

Through hands-on exercises, you'll step into the shoes of attackers, exploiting common vulnerabilities from developer environments and code repositories to dependencies and build/release tools. By the end of day one, you'll fully comprehend how exposed your software supply chain could be in this interconnected digital world



## Day 2:

From Vulnerability to Fortification - Securing Your Software Supply Chain

On the second day, we shift gears from understanding vulnerabilities to implementing robust defenses. We delve into industry standard frameworks such as SLSA and NIST SSDF, translating them into practical strategies for each component of your supply chain

You'll get your hands dirty by applying these strategies to secure your developer environments, code repositories, and CI/CD pipelines. You will learn how to use Software Composition Analysis (SCA) tools to manage package/dependency vulnerabilities effectively, create SBoM's for your own software. By the end of the course, you'll be equipped to transform your software supply chain from a security liability to an asset.

In modern, fast-moving organizations, keeping pace with digital transformation initiatives without compromising security is a growing conundrum. This course caters to everyone in the IT industry, from developers and engineers to IT managers, security analysts, and CTOs

The nature of software development has changed; it's high time our approach to securing it evolves too. This course offers not just knowledge, but practical skills to secure your software supply chain amidst this paradigm shift. It's no longer enough to secure your code. You need to secure your software's lifeline - the supply chain.

The class will contain a holistic view of software supply chain security both from attack and defense side, with focus on practical approach of learning with demos and hands-on labs -

- Introduction to Software Supply Chain
- Supply chain beyond code dependencies.
- Exploiting VS Code Workspaces
- Trojanizing IDE & Browser Extensions
- Exploiting Git & GitHub Misconfigurations
- Attacking CI Pipelines & custom runners
- Creating malicious dependencies
- Attacking package management ecosystems (like npm, gradle, etc.)
- Exploiting Deployment Systems (like GitHub & ArgoCD)
- Leveraging container images misconfigurations
- Looking at Cloud & Kubernetes attack paths
- Attacking Cloud Environment (IAM, Data, Configurations)
- Exploiting Kubernetes Misconfigurations & insecure defaults
- Introduction to Defense Strategies: SLSA and NIST SSDF
- 360° Security strategies & Top-down Defense from Governance
- Effective Inventory Management & SBOMs
- Establishing, storing & verifying Provenance
- Protecting The Assets & Establishing Baseline Security
- Cloud Audits
- Runtime Security
- Threat detection
- Responding and Recovering from the Security Breaches
- Mapping Different Roles and Responsibilities
- Securing yourself from the above discussed attacks.


Each section consists of - 
1. Overview and Case studies of the attack surface.
2. Hands-on Labs with vulnerable environment for the participants to play with.

The class is extensively hands-on with elaborate case studies from the real world and replicating the attacks to understand in depth on how to protect against them.

At the end of the two-day course, we will summarize the key points covered and offer suggestions for further learning. Each student will receive access to presentation slides, a constantly updating knowledge base, and a guide on setting up attack and defense infrastructure for self-practice purposes.


# KEY TAKEAWAYS
- Comprehensive understanding of software supply chain vulnerabilities and attacks to exploit these vulnerabilities and their defences.
- Expert guidance on implementing security measures across different - components of software supply chain.
- Knowledge of industry-standard security frameworks such as SLSA and NIST SSDF.

# WHO SHOULD TAKE THIS COURSE
- Software Developers and Engineers
- IT Managers
- Security Analysts
- DevOps Practitioners
- CTOs and Decision Makers in IT

# AUDIENCE SKILL LEVEL
Beginner

# STUDENT REQUIREMENTS
Basic knowledge of software development and IT security concepts is assumed. Familiarity with cloud platforms and CICD processes would be beneficial but not mandatory.

# WHAT STUDENTS SHOULD BRING
Our labs are cloud based, and a browser should be sufficient. However we will still suggest following hardware specs:

- Laptop with working browser and unrestricted internet access ( at least port 80 and 443. However, some web-socket connections might be required.)
- We would still recommend bringing a laptop with full administrative access in case any troubleshooting is required.

Please ensure if any HIDS or Firewall is installed, we have admin access to disable in case it interferes with the lab setup.

We will need to make accounts on services like GitHub/bitbucket/AWS etc for practical hands-on experience those accounts will be created as part of the program itself (Instructions will be provided prior to the class so students can come prepared).

# WHAT STUDENTS WILL BE PROVIDED WITH
- Lifetime access to course content via online portal. (This includes access to future updates to the course)
- Very Detailed step by step instruction manual for all challenges covered during the class.
- A Slide deck containing the slides covered during the class.
- Post-training capture-the-flag challenges designed to simulate real-world scenarios for practice.
- An Attack & Defend Infrastructure Guide to enable replication of the infrastructure in their own environment for practice purposes.
- A knowledge vault compatible with Obsidian / Logseq for continuous learning and note taking.

# TRAINERS
**[Anant Shrivastava](https://www.blackhat.com/asia-24/training/schedule/presenters.html#anant-shrivastava-33177)** is the founder of Cyfinoid Research which specializes in cybersecurity research. Previously he was a Technical Director at NotSoSecure Global Services, a boutique cyber security consultancy firm. He has been a trainer & a speaker at various international conferences (BlackHat-USA/ASIA/EU, Nullcon, c0c0n & many more). Anant also leads Open-Source projects, Tamer Platform & CodeVigilant. He also maintains the archive portal named Hacking Archives of India. In his free time, he likes to take part in open communities targeted towards spreading information security knowledge such as the null community, Garage4Hackers, hasgeek & OWASP.

**[Kumar Ashwin](https://www.blackhat.com/asia-24/training/schedule/presenters.html#kumar-ashwin-46998)** is a security professional specializing in web, cloud, and software supply chain security. With a notable presence in the field, he has delivered presentations and conducted training sessions for fellow security professionals at conferences such as x33fcon, BSides, and c0c0n. Actively participating in esteemed security communities like null - The Open Security Community, Winja, and DEFCON Cloud Village, Ashwin contributes through articulate speaking engagements at meetups and the creation of CTF challenges. Having transitioned from offensive security to security engineering, Ashwin brings a unique perspective to the discipline. His professional journey underscores a steadfast commitment to evolving methodologies, addressing the challenges inherent in security engineering, and ensuring the resilience of software supply chain.  Ashwin's expertise has proven instrumental in assisting numerous organizations in enhancing their security posture and safeguarding their assets. Check out Ashwin’s blog at https://krash.dev to learn more about his experiences and insights.