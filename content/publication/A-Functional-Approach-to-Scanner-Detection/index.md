+++
title = "A Functional Approach to Scanner Detection"
date = 2017-11-20

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Robert McAndrew", "Manaf Gharaibeh", "Haonan Wangz", "Stephen Hayne", "Christos Papadopoulos"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Preprint / Working Paper
# 4 = Report
# 5 = Book
# 6 = Book section
# 7 = Thesis
# 8 = Patent
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "Proceedings of the Asian Internet Engineering Conference (AINTEC '17), Bangkok, Thailand."
publication_short = ""

# Abstract.
abstract = "Detecting scanning in Internet traffic is a well-studied topic with no single, definitive approach. Among the proposed methods are two which are widely accepted, but with known limitations: one based on a static fanout ratio, and another on principal component analysis (PCA). We introduce a two-step procedure based on Functional PCA and k-means clustering which we argue provides significantly better robustness and data-driven applicability. We validate and compare using synthetic datasets with ''ground truth'' about anomalies on FTP and HTTP port traffic flows; our method identifies all scanners. We also compare approaches using NTP flow data prior to a reflective DDoS attack in 2014, providing a real-world example to illustrate the deficiencies of existing approaches and how they are addressed by our functional framework procedure. Lastly, we discuss insights into the traffic that cannot be obtained by the previous methods."

# Summary. An optional shortened abstract.
summary = ""

# Digital Object Identifier (DOI)
doi = "10.1145/3154970.3154976"

# Is this a featured publication? (true/false)
featured = false

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = []

# Slides (optional).
#   Associate this page with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Links (optional).
url_pdf = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# links = [{name = "Custom Link", url = "http://example.org"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
