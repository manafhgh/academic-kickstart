+++
title = "Assessing Co-Locality of IP Blocks"
date = 2016-04-10

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Manaf Gharaibeh", "Han Zhang", "Christos Papadopoulos", "Joh Heidemann"]

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
publication = "Proceedings of 19th IEEE Global Internet Symposium, San Francisco, CA, USA."
publication_short = ""

# Abstract.
abstract = "Many IP Geolocation services and applications assume that all IP addresses within the same /24 IPv4 prefix (a /24 block) reside in close physical proximity. For blocks that contain addresses in very different locations (such as blocks identifying network backbones), this assumption can result in a large geolocation error. In this paper we evaluate the co-location assumption. We first develop and validate a hierarchical clustering method to find clusters of IP addresses with similar observed delay measurements within /24 blocks. We validate our methodology against two ground-truth datasets, confirming that 93% of the identified multi-cluster blocks are true positives with multiple physical locations and an upper bound for false positives of only about 5.4%. We then apply our methodology to a large dataset of 1.41M /24 blocks extracted from a delay-measurement study of the entire responsive IPv4 address space. We find that about 247K (17%) out of 1.41M blocks are not co-located, thus quantifying the error in the /24 block co-location assumption."

# Summary. An optional shortened abstract.
summary = ""

# Digital Object Identifier (DOI)
doi = "10.1109/INFCOMW.2016.7562129"

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
url_pdf = "https://www.isi.edu/~johnh/PAPERS/Gharaibeh16a.pdf"
url_code = ""
url_dataset = "https://ant.isi.edu/datasets/geolocation/"
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
