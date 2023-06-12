---
title: AWS Security Masterclass

event: x33fcon 2023
event_url: https://www.x33fcon.com/#!t/aws.md

location: Pomorski Park Naukowo-Technologiczny
address:
  street: Aleja Zwycięstwa 96/98
  city: 81-451 Gdynia
  region: Poland

summary: Training on different attack & defense strategies related to AWS Cloud.
abstract: ''

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2023-05-31T13:00:00Z'
date_end: '2023-06-02T15:00:00Z'
all_day: true

# Schedule page publish date (NOT talk date).
publishDate: '2023-03-18T00:00:00Z'

authors: ['Kumar Ashwin','Chandrapal Badshah']
tags: ["training","aws","security","offensive","defensive"]

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
# TRAINING OUTLINE

AWS is the market leader in cloud computing. It has over 200 services under all three cloud computing models: IaaS, PaaS, and SaaS (and everything in between). Each service solves a different problem and has a different attack surface. Even if successfully compromised, each service would have a different blast radius.

Attacking and defending each AWS service will differ and involves understanding the nitty-gritty of each service. However, the principles are a handful. These principles remain almost the same for other cloud providers, despite their services working slightly differently.

Based on your current role or interests, you can train in one vertical - attack or defense. While such journeys cover the security of each service, the most significant disadvantage is that you are often pushed to think the other side won't or can't hinder you.

Moreover, Sun Tzu says in his book The Art of War: "If you know the enemy and know yourself, you need not fear the result of a hundred battles. If you know yourself but not the enemy, for every victory gained you will also suffer a defeat. If you know neither the enemy nor yourself, you will succumb in every battle."

In this 3-day hands-on training, you will attack and defend AWS services, giving you the experience of looking at the same environment from both viewpoints. The training will include guided walkthroughs, real-world scenarios, and coverage of tools that can be used to attack and audit AWS environments. After this training, you will learn different tactics, techniques, and procedures to attack and defend the AWS cloud from Day One. 

Attackers will learn a holistic way to approach targets in a pentest. On the other hand, defenders will learn the common issues with AWS services, how to think in graphs, and how to prioritize tasks to reinforce security. Overall, this training will help you find issues/solutions that automated tools fail to see.

## Attack
- Shared Responsibility Model from Attacker Perspective
- Getting into Hacker's Mindset
- Identifying the Attack Surface
	- Cloud Service, Account Details, Exposed Assets, etc.
- Attacking CI/CD Pipeline to gain Cloud Access
	- Secrets Management Issues, Code Injection, etc.
- Attacking Load Balancers and WAF.
- Attacking Containers and Kubernetes.
- Esclating Privileges Left, Right and Center.
	- Leveraging the initial access of different services - S3, EC2, KMS, SNS, EBS, etc.
	- Leveraging/Analyzing IAM Policies to gain access to different access levels using passrole, assume role, and other techniques.
- I am in. Now what?
	- Backdoor Techniques using services like S3, EC2, Lambda, etc.
	- Shadow User
	- Excessive resource usage
- Defense Evasion Techniques
	- Guard Duty, AWS WAF, AWS Shield, etc.

Post the supervised learning, we will be having an unsupervised learning activity as a CTF.


## Defend
- Real World AWS Environments
- Defenders' Methodology
- Shared Responsibility Model
- Know Thyself! - Visualizing your attack surface
	- Introduction to Steampipe and Cartography
- AWS Services for Security (Compare and Contrast)
	- Config, Inspector, GuardDuty, Resource Explorer, etc.
- Building upon Secure Foundations
- Order and it shall be followed
	- Management account, Organizational Unit and Child accounts
	- Service Control Policies (SCPs)
	- Delegated Administrator
	- Tag management & Backup policy
- Realtime Monitoring
	- Detecting Brute Force Attack
	- Automated Alerts
- AWS Account Security
	- Securing IAM
- Compute Security
	- IMDSv1 vs IMDSv2 
	- Securing AMI, ECR images, backups, snapshots, etc.
- Data Security
	- Classifying Data
	- Encrypt, Encrypt, Encrypt!
- Finding Attack Paths with Ease
- Incident Response Scenarios

Post the supervised learning, you will defend a vulnerable-by-design infrastructure. 


## WHO SHOULD ATTEND?
- Pentesters
- Cloud/IT Professionals
- DevSecOps Engineers
- Solutions Architects
- Experienced cybersecurity enthusiasts who want to take their skills to the next level.


## WHAT TO BRING?
- Admin/root access
- A virtualisation software (virtualbox / VMWare) pre-installed
- 8 GB RAM and 20 GB free disk space dedicated (for Linux virtual image)
- Minimum of 8 GB on host system to support virtual image (preferable)

Note: Macbooks with M1 chips are not supported due to virtualization issues.


## TRAINING PREREQUISITE
- Requires familiarity with common command line syntax and a working knowledge of cloud services.


## WHAT ATTENDEES WILL BE PROVIDED?
- Slides, practical materials, tools, and cheat sheets.
- Access to your own lab for practical exercises, installed with targets and capabilities.


## WHAT NOT TO EXPECT?
- Anything related to GCP, Azure, and any other CSPs.
- Cloud Native Security in depth or Cloud Workload Protection.

## ABOUT THE TRAINERS

### Kumar Ashwin
Kumar Ashwin is a skilled information security professional with a focus on web security, cloud security, and DevSecOps. He actively participates in various security communities, including The Open Security Community, Winja, and DEFCON Cloud Village, by speaking at meetups and creating CTFs. Ashwin has also spoken at conferences such as Bsides and c0c0n. As an offensive security specialist, Ashwin excels in identifying vulnerabilities and preventing attacks. His expertise has helped numerous organizations improve their security posture and protect their assets. Check out Ashwin's blog at https://krash.dev to learn more about his experiences and insights.

### Chandrapal Badshah
Chandrapal Badshah is a Cloud Security Engineer and a Researcher. While his engineer mind secures cloud accounts during the day, his research mind strives to find cloud issues (at scale) during the night. He has experienced security wearing different hats during his career - first as a Product Security engineer, next as a Security Research lead, and now as a person fully focused on Cloud and DevSecOps. He is an AWS Certified Security professional as well. He is a volunteer at Defcon Cloud Village. He has been a co-trainer at BlackHat Asia training and has given talks at community Meetups like null and OWASP. He blogs about his experiments and experiences at https://badshah.io.