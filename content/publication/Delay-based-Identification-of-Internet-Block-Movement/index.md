+++
title = "Delay-Based Identification of Internet Block Movement"
date = 2020-04-08T02:18:45-06:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Manaf Gharaibeh", "Christos Papadopoulos", "John Heidemann", "Craig Partridge"]

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
publication_types = ["4"]

# Publication name and optional abbreviated version.
publication = "Technical Report TR-20-101, Colorado State University"
publication_short = ""

# Abstract.
abstract = "Some IP blocks occasionally change their physical location, such as when blocks are transferred to different organizations, or repurposed within an organization. IP geolocation systems need to identify such changes to provide accurate results for location-dependent applications such as geo-blocking and online fraud prevention. We propose an efficient method to identify IP blocks that move, since full geolocation is expensive and unnecessary for blocks that do not move. Our approach uses persistent changes in latency as an indicator of block movement, tracking all ping-responsive IPv4 /24 blocks from a handful of globally distributed vantage points. We estimate around 2.1% of the 3.77M /24 blocks we studied have changed location at least once in the last 3 months of 2018. We find that the remaining blocks were consistently RTT-stable during the same period, suggesting that their locations were also stable. We validate a random sample of blocks we identify as moving and confirm 80% (41 of 51) through traceroutes."

# Summary. An optional shortened abstract.
summary = ""

# Digital Object Identifier (DOI)
doi = ""

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
url_pdf = "https://www.cs.colostate.edu/TechReports/Reports/2020/tr20-101.pdf"
url_code = ""
url_dataset = "https://ant.isi.edu/datasets/outage/"
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
