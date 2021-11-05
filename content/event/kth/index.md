---
title: On the design of cooperative maneuvers for CAV in traffic flow

event: Automatic Control Department, KTH
event_url: https://example.org

location: KTH
address:
  street: Brinellvägen 8
  city: Stockholm
  region: SV
  postcode: '11428'
  country: Sweden

summary: Recent works combining traffic flow theory and control problems for CAVs.
abstract: "Vehicle platooning in particular truck platooning has attracted substantial attention due to its pronounced benefits in saving energy and promising business model in freight transportation. However, one prominent challenge for the successful implementation of these strategies is the safe and efficient interaction with surrounding traffic, especially at network discontinuities where mandatory lane changes may lead to the decoupling of truck platoons. In this talk, some control methods for vehicle platoons are presented in the presence of traffic flow.  In the first part, an efficient method for splitting a platoon of vehicles near network merges is considered. The control problem is cast as a bi-level hierarchical control problem where the supervisory layer is tied to classic traffic flow theory. The decisions taken at this level include optimal vehicle order after the merge, new equilibrium gaps of automated trucks at the merging point, and anticipation horizon that the platoon members start to track the new equilibrium gaps. In the second part of the talk, a differential game framework is presented to design the system optimum strategy for a network of cooperative vehicles interacting at a merging bottleneck with a simplified vehicle dynamics model. An optimum strategy is found by minimizing the joint cost of interacting vehicles while respecting behavioral and physical constraints. The full differential game is cast as a set of sub-problems regularly expressed as standard optimal control problems that can be solved efficiently. Numerical examples show the feasibility of the approach in capturing the nature of conflict and cooperation during the merging process."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2019-04-23T15:00:00Z"
date_end: "2019-04-23T16:00:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: "2019-04-23T10:00:00Z"

authors: ["Andres Ladino", "Aurelien Duret", "Meng Wang"]
tags: ["Truck Platooning","Connected & Automated Vehicles", "Vehicle Merging"]

featured: true

image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
  focal_point: Right

links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/aladinoster
url_code: ""
url_pdf: ""
url_slides: "http://bit.ly/KTH_201904"
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
projects:
- ensemble
---