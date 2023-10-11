---
title: Common Misconfigurations in your Kubernetes Cluster and What can you do about it?

event: c0c0n XV
event_url: https://india.c0c0n.org/2022/home

location: Kochi, India

summary: "The talk covers securing Kubernetes clusters by addressing common misconfigurations and vulnerabilities."
abstract: ""

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2022-09-23T16:45:00Z"
date_end: "2022-09-23T17:30:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: "2022-09-23T00:00:00Z"

links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/0xCardinal
url_code: ""
url_pdf: ""
url_slides: "../slides/Common Misconfigurations In Your Kubernetes Cluster And What.pdf"
url_video: ""

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption: ''
  focal_point: Right

---

For defining and creating a scalable solution, containers and orchestration play a very
important role. Where container eases out the product development process, orchestration
ease out the scalability problem. Orchestrators are something that helps in the management
of multiple containers, one such orchestrator is Kubernetes.

Kubernetes is increasing in popularity every day because of the use cases but it is found that
product teams (development, platform, security, etc.) struggle to understand these modern
technologies. This opens a window for error, which leads to the misconfigured Kubernetes
environment. World Economic Forum’s The Global Risk Report 2022 revealed that human
error was a major contributing factor to 95% of breaches. Kubernetes and containers, while
powerful, were designed for developer productivity, not necessarily security.

In this talk, we will be looking at some common misconfigurations that can happen in your
Kubernetes Clusters and how can we secure them? Here are some of the things we look at
among many others look at -
- Namespaces Security
- Over-permissive containers
- Kubernetes API and its components
- Insecure defaults
- Configuration Review
- Container Security

We will be looking at scenario-based examples, that will give more context to the real-world
attacks and vulnerabilities and how we go about fixing and defending them. After this talk,
you will learn about how to secure your Kubernetes cluster and make your product great
again.