---
title: 'DYNAMOS Paper Presented at ICSA 2024'
authors:
- Aleandro
- Jorrit
tags:
- Academic
categories:
- News
date: "2024-07-11T00:00:00Z"
featured: false
draft: false

summary: "Visiting India to present the lessons learned from developing DYNAMOS in ICSA 2024!"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Placement options: 1 = Full column width, 2 = Out-set, 3 = Screen-width
# Focal point options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

[Jorrit](https://cci-research.nl/author/jorrit-stutterheim/) (right) and [Aleandro](https://cci-research.nl/author/aleandro-mifsud/) (left) attended the [International Conference of Software Architecture (ICSA) 2024](https://conf.researchr.org/home/icsa-2024) in Hyderabad India to present "DYNAMOS: dynamic microservice composition for data-exchange systems, lessons learned", authored by Jorrit, Aleandro and [Ana](https://cci-research.nl/author/ana-oprescu/) in the [Software Architecture in Practice](https://conf.researchr.org/track/icsa-2024/icsa-2024-software-architecture-in-practice-track) track. ICSA is the premier venue for practitioners and researchers interested in software architecture, in component-based software engineering and in quality aspects of software and how these relate to the design of software architectures. 

The conference featured interesting lectures and workshops on topics including distributed systems, green software engineering, software architecture and machine learning, large language models, and digital twin technology, among others. Additionally, many opportunities to socialize and network were available, both during the conference sessions and at various social events.

## Abstract

Data exchange has become increasingly important in modern business and research.

Consequently, many initiatives are being developed worldwide to facilitate open data exchange in secure distributed marketplaces. Ideally, each party maintains control over their data and implements access through legal contracts, in the form of programmable policy. Such policy would express \textbf{where} the data exchange takes place, and \textbf{who} has access to the data.

Inspired by how traditional Operating Systems abstract the complexities of computer architectures into standardized core functions, this research focuses on abstracting different data exchange patterns into a unified set of core data exchange microservices that adhere to agreed-upon data exchange policies. DYNAMOS implements a distributed data exchange platform and recreates real-life data exchange use cases. It is designed to be self-adaptive, utilizing extendable algorithms to generate dynamic microservice compositions and dynamically choose archetype patterns, influenced by policy, user input, or system events.

In our study, we highlight key insights from our experience with a dynamic microservice platform. Employing sidecars for communication abstraction, protocol buffers for strict interface definition, and ephemeral single-use jobs for improved security emerged as pivotal strategies. However, these approaches do introduce a trade-off between operational speed and especially system complexity.
