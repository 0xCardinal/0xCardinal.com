---
draft: false
title: Are Your Containers Really Secure?

event: Red Team Security Summit
event_url: https://www.linkedin.com/posts/redteam-security-summit_redteamsecuritysummit-hackingconference-cyberdefense-activity-6875084143282257921-R1UE?utm_source=linkedin_share&utm_medium=ios_app

location: Remote

summary:  The talk covers basics of containers, docker primer and how to secure Docker containers pre-build.
abstract: ""

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2021-12-18T13:00:00Z"
date_end: "2021-12-18T13:45:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: "2017-01-01T00:00:00Z"

authors: ["Kumar Ashwin"]
tags: ["containersecurity", "docker", "Dockerfile"]

# Is this a featured talk? (true/false)
featured: false

image:
  caption: ''
  focal_point: Right

links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/0xCardinal
url_code: ""
url_pdf: ""
# url_slides: "https://speakerdeck.com/0xcardinal/getting-started-with-dfir-payatu-webinar"
url_video: ""

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.

---

Organizations have shifted to cloud native solutions, which rely on containers for scalability and resilience, which also increase the attack surface when looked at from an attackers point of view. It becomes very important to make sure that the containers are secure in nature. In this talk, I will be talking about 

- Efficiently creating container images.
- What are the best practices and ways to build secure container images?
- How you can perform active scanning on containers?

This talk will not cover, 

- Container Orchestration (Kubernetes or similar)