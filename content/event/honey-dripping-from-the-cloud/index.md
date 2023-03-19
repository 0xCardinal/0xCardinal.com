---
draft: false
title: Honey Dripping from the Cloud

event: Bsides BHAM
event_url: 

location: Remote

summary: Talking about the attack and defend techniques of AWS Infrastructure and how we can pump up the security by implementing HoneyPots and utilizing the logging & Monitoring Capabilities.
abstract: ""

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2021-10-15T11:00:00Z"
date_end: "2021-10-15T11:50:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: "2017-01-01T00:00:00Z"

authors: ["Kumar Ashwin", "Hrushikesh Kakade"]
tags: ["aws","honeypots","security"]

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
url_slides: "https://speakerdeck.com/0xcardinal/honey-dripping-from-the-cloud-bsides-bham"
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

<div class="text-center"><iframe class="speakerdeck-iframe" frameborder="0" src="https://speakerdeck.com/player/3cf1c03f86f94c56b613e492d96b4d7e" title="Honey Dripping From The Cloud | BSides BHAM" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true" style="border: 0px; background: padding-box padding-box rgba(0, 0, 0, 0.1); margin: 0px; padding: 0px; border-radius: 6px; box-shadow: rgba(0, 0, 0, 0.2) 0px 5px 40px; width: 560px; height: 314px;" data-ratio="1.78343949044586"></iframe></div><br>

Migrating to the cloud opens up new possibilities for an organization, but at the same time, it also increases the attack vectors for an adversary. In the cloud, the perimeter security alone won't help in keeping the bad actors away. Organisations too need to think out of the box.

Cloud is mostly secure by default, so if we see the responsibility matrix, most of the activities are being handled by the cloud provider but there are certain things that fall on the tenant. The majority of the vulnerabilities are found because of the misconfiguration issues in these three sections.

- Everything Client Side
- Data in Transit and Rest
- Identity and Access Management

This talk will be about looking at a cloud infrastructure from an attacker's point of view and discovering how honeypots can help the defenders, keeping the bad actors away from the cloud infrastructure of your organisation.

We will be covering:
- Attacker's point of view on attacking AWS infrastructure.
- Deployment of some luring components (like Honeypots and Honey Tokens)
- Benefits of this deployment from a defender's perspective.