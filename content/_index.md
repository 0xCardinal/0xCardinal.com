---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text: ''
      
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Senior Security Engineer
          company: Tide Platform Limited (Tide)
          company_url: 'https://tide.co/'
          location: Remote
          date_start: '2023-11-13'
          date_end: ''
          description: 

        - title: Security Engineer
          company: DeepSource
          company_url: 'https://deepsource.com/'
          location: Bengaluru
          date_start: '2023-02-20'
          date_end: '2023-09-01'
          description: |2-
              - Implement and enforce security practices throughout the entire organization.
              - Implemented security tooling such as Trivy, Trufflehog, and others, and ensured the integration of GitHub security features into the DevOps pipeline. Collaborated cross-functionally to drive widespread adoption of these security measures.
              - Research on different exploits reported by tool to determine it's impact and exploitability using frameworks like EPSS.
              - Conducted penetration tests on feature releases and managed annual third-party security assessments to ensure software security and compliance.
              - Implemented a centralized vulnerability management solution to efficiently manage and triage security issues reported by tools like Trivy and ScoutSuite-powered makeshift CSPM.
              - Conducted routine access audits, enforced the least privilege principle, restricted access to sensitive components and data to only when necessary, and maintained comprehensive access logs for these instances.
              - Played a pivotal role in working towards attaining SOC2 and ISO27001 compliance certifications, demonstrating a commitment to industry- leading security standards.
              - Used Terraform for automated resource provisioning via pull requests, enhancing security and consistency while reducing operational risks.
              - Actively led the codebase and GitHub organization migration process, including restructuring and access control, to ensure a secure and organized transition.
              - Collaborated on enhancing deployment security with ArgoCD, optimizing the management of GitOps-driven infrastructure and ensuring secure, automated deployments.
              - Efficiently triaged reports from our open bug bounty program, prioritizing and addressing security vulnerabilities to enhance overall system resilience.
              - Conducted phishing drills to educate and raise awareness among team members about security threats and phishing attack vigilance.

        - title: Security Consultant - Program Manager
          company: Payatu
          company_url: 'https://payatu.com/'
          location: Pune
          date_start: '2022-05-01'
          date_end: '2023-02-14'
          description: |2-
              -	Managed entire delivery process of all the projects in the company ensuring the quality of work is being delivered to the customer.
              -	Acts as first point of contact for customers to resolve any issues.
              -	Technical Lead for Projects.
              -	Coordinating with different departments like HR, Marketing, Finance to get the best for the consultants and customers.

        - title: Security Consultant
          company: Payatu
          company_url: 'https://payatu.com/'
          location: Pune
          date_start: '2021-07-01'
          date_end: '2022-05-01'
          description: |2-
            -	Performed penetration testing on a wide range of web technologies to identify critical vulnerabilities affecting the business, such as Content Manipulation and SQL Injection.
              -	Experienced in working with automated and manual penetration testing methodology to deliver quality results.
              -	Performed cloud configuration review and penetration testing to find critical misconfiguration in client’s infrastructure.
              -	Automated workflows   and created DevSecOps pipelines and performed penetration testing on CI/CD pipelines to find vulnerabilities.
              -	Worked on in-house open-source projects like https://securecode.wiki and https://cybersecwiki.com to contribute to infosec community.
              -	Hosted and managed Payatu Hiring CTF, contributed to creating challenges, hosting, and maintaining infrastructure, moderating Discord, etc. post that taking interviews of the top candidates to hire them.

        - title: Security Consultant Intern
          company: Payatu
          company_url: 'https://payatu.com/'
          location: Pune
          date_start: '2021-01-18'
          date_end: '2021-06-18'
          description: |2-
              * Working with clients to pentest web applications.
              * Developed front-end solution to make the secure code wiki public - [securecode.wiki](https://securecode.wiki) and also created its CI/CD pipeline.
              * Research on real time scenarios and tools.
              
        - title: Software Development Intern
          company: RevMeUp
          company_url: ''
          location: Remote
          date_start: '2020-05-01'
          date_end: '2020-08-31'
          description: |2-
              * Developed an admin panel to monitor and manage data and requests from the mobile application.
              * Tech Stack used:  HTML/CSS, Bootstrap, NodeJS and MongoDB

    design:
      columns: '2'
  - block: experience
    content:
      title: "Community"
      subtitle: Volunteering work in different tech. communities.
      date_format: Jan 2006
      items:
        - title: Chapter Lead 
          company: null - The Open Security Community
          company_url: 'https://null.community/'
          location: Pune, India
          date_start: '2022-05-20'
          date_end: '2023-02-14'
          description: |2-
              - Re-started null Pune Chapter Monthly Meetups and other types of meetings like null Humla, Puliya and workshops along with concepts like news bytes and networking hour.
              - Organizing monthly events, arranging venues, inviting speakers, and other duties are among the responsibilities.
        - title: Crew member
          company: DEFCON Cloud Village
          company_url: 'https://cloud-village.org/'
          location: Remote
          date_start: '2021-07-06'
          date_end: ''
          description: |2-
              * Developed pre-CTF challenges for Social Media and also challenges for the main event.
              * Worked on different cloud providers - AWS, GCP, Azure, Digital Ocean & Alibaba while working on the CTF.
              * Handled Social Media aspect of strategising posts for better reach and engagements and also designing creatives for the event.
        - title: Moderator & Challenge Developer
          company: "WinjaCTF"
          company_url: 'https://winja.site/'
          location: Remote
          date_start: '2021-03-06'
          date_end: ''
          description: |2-
              * Developed CTF challenges for the Winja CTF events at nullcon 2021 (06th Mar, 2021) and at c0c0n 2021 (12th Nov, 2021).
        - title: Volunteer
          company: "null - The Open Security Community"
          company_url: 'https://null.community/'
          location: Remote
          date_start: '2020-09-18'
          date_end: ''
          description: |2-
              * Managing null Study Groups for 7 different domains of information security. Helping the newcomers, get exposed to industry grade learning experience. Responsibilities involved conducting weekly/bi-weekly meetups, finding mentors, etc.
              * Moderator for null Community Discord Server.
              * Worked in the OSINT project, contributed in gathering information from the government websites and presenting them in an easy-to-consume form.
        - title: Core Team Member
          company: "Facebook Developers Circle: Pune"
          company_url: 'https://www.facebook.com/groups/DevCPune'
          location: Remote
          date_start: '2019-11-21'
          date_end: '2021-06-21'
          description: |2-
              * Moderating talks, sessions and any events that fall under the umbrella of DevC: Pune.
              * Developed CTF security centric challenges, for developers to learn about security.
              * Generates content or organizes discussion for the members.
    design:
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: ''
          date_end: ''
          date_start: '2020-03-10'
          description: ''
          organization: Microsoft
          organization_url: https://www.microsoft.com
          title: "MTA: Security Fundamentals"
          url: 'https://docs.microsoft.com/en-us/learn/certifications/exams/98-367'
        - certificate_url: ''
          date_end: '2023-11-05'
          date_start: '2020-11-06'
          description: ''
          organization: EC-Council
          organization_url: https://www.eccouncil.org/
          title: 'Certified Ethical Hacker (Practical)'
          url: https://www.eccouncil.org/programs/certified-ethical-hacker-ceh-practical/
        - certificate_url: ''
          date_end: ''
          date_start: '2021-04-16'
          description: ''
          organization: Amazon Web Services (AWS)
          organization_url: https://www.aws.training/
          title: 'AWS Security Fundamentals (Second Edition)'
          url: 'https://www.aws.training/Details/eLearning?id=34259'
    design:
      columns: '2'
  - block: collection
    id: talks
    content:
      page_type: event
      count: '1'
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
  - block: contact
    id: contact
    content:
      title: Say Hi!
      subtitle:
      text: ''
      # Contact (add or remove contact options as necessary)
      email: ashwin@0xcardinal.com
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: Ping Me!  
          link: 'https://twitter.com/0xCardinal'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: true
    design:
      columns: '2'
---
