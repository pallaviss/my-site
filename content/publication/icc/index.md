+++
title = "Implementation and Analysis of Offset-Free Explicit Model Predictive Controller on FPGA"
date = 2019-01-18T00:08:36+05:30


# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Adhau S", "Phalke K", "Nalawade A", "Ingole D", "Patil S", "Sonawane D"]
# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "In *5<sup>th</sup> Indian Control Conference (ICC)*, IEEE, IIT Delhi, India."
publication_short = "In *ICC*"

# Abstract.
abstract = "It is well-known that the real-time implementation of MPC is cumbersome because of the huge burden of solving QP problem on-line at each sample time. Due to this, traditionally MPC has been mainly restricted to processes with rather slow dynamics, such as the ones encountered in the oil and gas refineries. However, recent algorithmic advances (such as the explicit MPC) allowed the application of MPC to problems arising in the automotive or power electronics industry where the time scales are in the milli- to microsecond range. This paper focuses on the FPGA implementation of offset-free explicit MPC and its detailed analysis for the position control of PMDC motor. We show the analysis of controller computational complexity in terms of memory, resource utilization, clock and power consumption. Effect of various tuning parameters on the number of regions is also presented with respect to the changing prediction horizon length. Finally, the performance of implemented offset-free explicit MPC is compared with the standard explicit MPC and PI controller for reference-tracking, constraints handling, and disturbance rejection. Results indicate that the performance of offset-free explicit MPC is superior but at the cost of increased memory footprint."

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
#   projects = []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#   slides = "example-slides"

# Links (optional).
#url_pdf = ""
url_preprint = "https://saketadhau.netlify.com/publication/icc/icc.pdf"
url_code = ""
url_dataset = ""
url_project = ""
url_slides = "https://saketadhau.netlify.com/publication/icc/icc-ppt.pdf"
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# links = [{name = "Custom Link", url = "http://example.org"}]

# Does this page contain LaTeX math? (true/false)
math = false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  #caption = "Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++