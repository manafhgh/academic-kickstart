+++
title = "BotDigger: Detecting DGA Bots in a Single Network"
date = 2016-04-07

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Han Zhang", "Manaf Gharaibeh", "Spiros Thanasoulas", "Christos Papadopoulos"]

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
publication = "Proceedings of the 2016 Network Traffic Measurement and Analysis Conference (TMA '16), Louvain La Neuve, Belgium."
publication_short = ""

# Abstract.
abstract = "To improve the resiliency of communication between bots and C&C servers, bot masters began utilizing Domain Generation Algorithms (DGA) in recent years. Many systems have been introduced to detect DGA-based botnets. However, they suffer from several limitations, such as requiring DNS traffic collected across many networks, the presence of multiple bots from the same botnet, and so forth. These limitations make it very hard to detect individual bots when using traffic collected from a single network. In this paper, we introduce BotDigger, a system that detects DGA-based bots using DNS traffic without a priori knowledge of the domain generation algorithm. BotDigger utilizes a chain of evidence, including quantity, temporal and linguistic evidence to detect an individual bot by only monitoring traffic at the DNS servers of a single network. We evaluate BotDigger’s performance using traces from two DGA-based botnets: Kraken and Conflicker. Our results show that BotDigger detects all the Kraken bots and 99.8% of Conficker bots. A one-week DNS trace captured from our university and three traces collected from our research lab are used to evaluate false positives. The results show that the false positive rates are 0.05% and 0.39% for these two groups of background traces, respectively."

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
url_pdf = "https://tma.ifip.org/2016/papers/tma2016-final56.pdf"
url_code = "https://github.com/hanzhang0116/BotDigger"
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
