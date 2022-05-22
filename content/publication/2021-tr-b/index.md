+++
title = "Enforcing optimal routing through dynamic avoidance maps"
date = 2021-05-16T12:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Leclercq L.","Ladino A.", "Becarie C."]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "In *Transportation Research Part B*."
publication_short = "In *TR-B*"

# Abstract and optional shortened version.
abstract = "This paper presents a new concept for operating traffic management at a sizeable urban scale. The overall principle is to partition the network into multiple regions, where traffic conditions should remain optimal. Instead of monitoring the inflow, like for perimeter control, deviations in regional mean speed compared to the reference are transformed into avoidance levels by a centralized controller. That information is broadcasted to vehicles through a public avoidance map. The onboard navigation systems then interpret this map to deliver individual route guidance according to the avoidance levels. In that way, the concept tends to distribute vehicles in the network optimally while preserving privacy. In addition to the controller parameters itself, three other critical parameters define the system: the safety distance, the controller time horizon, and the region sizes. Thorough sensitivity analysis leads to the optimal setting. The concept is proven effective using microsimulation for both a Manhattan and a realistic network. The total travel times is improved by about 15% when traffic is severely congested compared to the uncontrolled case. In the meantime, the mean individual travel distance increase for rerouted vehicles is kept below 10%. Those results have been obtained with a simple decentralized reactive control framework, i.e., an individual proportional feedback system independently governs each region. More advanced formulations introducing cooperation between the regions are also tested. In a nutshell, this paper is a proof of concept for a new control system that appears both practical and valuable to alleviate congestion in urban areas"
abstract_short = "This paper addresses the problem of operating traffic mangement at a sizable urban scale via avodance maps and optimal rerouting"

# Is this a selected publication? (true/false)
featured = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = ["symupy"]

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags =  ["Optimal route guidance","Urban traffic control", "Avoidance Maps","System Optimum"]

# Links (optional).
url_pdf = "https://www.sciencedirect.com/science/article/pii/S0191261521000813"
url_preprint = "http://bit.ly/TR-B_EOTDAM2021"
url_code = "https://github.com/licit-lab/vanishing-control"
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Digital Object Identifier (DOI)
doi = "10.1016/j.trb.2021.05.002"

# Does this page contain LaTeX math? (true/false)
math = true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
[image]
  # Caption (optional)
  caption = "Taken from **Paper**"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Smart"
+++
