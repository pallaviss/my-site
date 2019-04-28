+++
title = "Embedded Model Predictive Control on Low-Cost Low-End Microcontroller for Motor Speed Control"
date = 2018-10-18T01:12:51+05:30

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Adhau S", "Dani S", "Ingole D", "Patil S", "Sonawane D"]
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
publication = "In *4<sup>th</sup> International Conference for Convergence in Technology (I2CT)*, IEEE, Mangalore, India."
publication_short = "In *I2CT*"

# Abstract.
abstract = "It is very well-known that the implementation of Model Predictive Controller (MPC) on embedded platforms is challenging due to computational complexities associated while solving an optimization problem. Although, there are many efficient embedded implementations existing by now, but for faster, more dynamic and non-linear control applications, no cost effective and memory efficient embedded solutions are present. In this paper, we show the implementation of embedded explicit MPC for a motor speed control application on a low-cost 8 bit PIC 18 series microcontroller from Microchip Technology. The offset-free explicit MPC is designed for reference tracking and constraints and disturbance handling. The developed control law is exported to low-level C code and utilized in hardware-in-the-loop co-simulations. We present the results of memory demand and control performance under various operating scenarios. The presented results show that the developed embedded MPC utilize about 40% of RAM and 92% of ROM for prediction horizon up to 3 samples. The performance of developed MPC is compared with the conventional PI controller. Overall results show that the presented approach is cost effective, portable, and gives better performance than the PI controller."

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
url_preprint = "https://saketadhau.netlify.com/publication/i2ct/i2ct.pdf"
url_code = ""
url_dataset = ""
url_project = ""
#url_slides = "https://saketadhau.netlify.com/publication/icc/icc-ppt.pdf"
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# links = [{name = "Custom Link", url = "http://example.org"}]

# Does this page contain LaTeX math? (true/false)
math = true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  # caption = "Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
