---
title: Attacking CI/CD Environments - OWASP Trainings

event: OWASP Spring Training 2024
event_url: https://www.eventbrite.com/e/owasp-spring-virtual-training-tickets-848566494227?aff=oddtdtcreator

location: Online

summary: In this course, we take an approach from basics to advanced guidance. We start with understanding how CI / CD systems work under the hood and then understand their position in a corporate IT environment. We focus on exploiting both self-hosted environments as well as SaaS-based environments. 
abstract: ''

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2024-05-14T13:00:00Z'
date_end: '2024-05-16T15:00:00Z'
all_day: true

# Schedule page publish date (NOT talk date).
publishDate: '2024-03-20T15:00:00Z'

authors: ['Kumar Ashwin', 'Anant Shrivastava']
tags: ['supplychain', 'cicd', 'attack']

# Is this a featured talk? (true/false)
featured: true

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
# TRAINING TITLE
Attacking CI/CD Environments

# TRAINING SCHEDULE
- Start Date: May 14, 2024
- End Date: May 16, 2024

# TRAINING OBJECTIVES
CI / CD systems are obnoxiously present and sprayed across modern enterprise environments. With the current world focusing on faster delivery, and faster production CI / CD has taken a prominent role in the development world. Rapid adoption of these technologies has meant that a lot of the security precautions are thrown out of the window and insecure by default settings are in place. We have created this course to focus on Attacking CI CD environments as a way in for attackers.

In this course, we take an approach from basics to advanced guidance. We start with understanding how CI / CD systems work under the hood and then understand their position in a corporate IT environment. We focus on exploiting both self-hosted environments as well as SaaS-based environments. 

# TRAINING LEVEL
Beginner

# TRAINING OUTLINES
## Day 1
Overview of CI/CD Environments
- Definition and importance of CI/CD
- Key components of CI/CD pipelines
- Source control
- Build automation
- Testing
- Deployment
- Monitoring
- CI/CD in the software development life cycle (SDLC)

Introduction to CI/CD Attacks
- Why do attackers target CI/CD pipelines?
- Rapid deployment as an attack surface
- Potential for automating attacks
- Common attack vectors in CI/CD environments
- Real-world examples of CI/CD attacks

CI/CD Attacks in Different Environment
- Environments
  - GitHub
  - Jenkins
  - GitLab CI
  - Travis CI
- Unique features and use cases
- Comparative analysis of different CI/CD platforms

## Day 2
Environment Specific Attacks (GitHub)
- Initial Accesses & Conditions
- Enumeration Strategies
- GitHub way of CI/CD Systems
- Insecure Defaults
- Context Injection
- Custom Runner Misconfigurations
- Workflow Manipulation
- Malicious Action Creation & Injection
- Secret Exposure
- Un-authz Workflow Executions
- Workflow Bypass Techniques
- Webhooks and External Integrations Abuse
- Secrets in CI/CD Logs

Environment Specific Attacks (Jenkins)
- Jenkinsfile Tampering
- Unauthorized Access and Privilege Escalation
- Plugin Vulnerabilities Exploitation
- Build Script Manipulation
- Build Artifacts Tampering
- Script Console Abuse
- Jenkins API Exploitation

## Day 3
Environment Specific Attacks (GitLab CI)
- Pipeline Configuration Tampering
- Job Script Manipulation
- API Token and Credentials Exposure
- Build Artifacts Manipulation
- Runner Exploitation
- Webhooks and External Integrations Abuse
- Secrets in CI/CD Logs
- Unauthorized Pipeline Execution
- Misconfigured Job Dependencies
- Insecure Container Images

Cloud Providers CI/CD Systems' Attack Vectors
- Insecure IAM
- CI/CD Systems Misconfigurations
- Cross-service Misconfigurations

Using CI/CD Systems as Attacker's Tools
- C2
- Stealth

The course will be followed by a Capture-The-Flag event, where the participants can implement their learnings and hack a vulnerable-by-design environment on the last day of the training. 
 


# WHAT TO BRING?
Our labs are cloud-based, and a browser should be sufficient. However, we will still suggest the following hardware specs:
- Laptop with working browser & and unrestricted internet access (at least port 80 and 443. However, some web-socket connections might be required.)
- We would still recommend bringing a laptop with full administrative access in case any troubleshooting is required.
- As part of the program, participants will create accounts on platforms like GitHub and Bitbucket for hands-on activities. Clear instructions will be provided in advance, and creating these accounts is free of charge. 

# ABOUT THE TRAINER
**Anant Shrivastava** is a highly experienced information security professional with over 15 years of corporate experience. He is a frequent speaker and trainer at international conferences and is the founder of Cyfinoid Research, a cyber security research firm. He leads open source projects such as Tamer Platform and CodeVigilant and is actively involved in information security communities such as null, OWASP, and various bsides and defcon groups.
 

**Kumar Ashwin** is a security professional specializing in web, cloud, and software supply chain security, and is highly regarded in the field. He has presented at conferences like x33fcon, BSides, and c0c0n, and actively contributes to security communities like null, Winja, and DEFCON Cloud Village. Transitioning from offensive security to security engineering, Ashwin offers a unique perspective, emphasizing evolving methodologies and ensuring software supply chain resilience. His expertise has aided numerous organizations in bolstering their security posture. Visit his blog at https://krash.dev for more insights.