+++
title = "Implementation and Analysis of Nonlinear Model Predictive Controller on Embedded Systems for Real-Time Applications"
date = 2019-02-17T23:44:37+05:30

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Adhau S", "Patil S", "Ingole D", "Sonawane D"]

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
publication = "In *European Control Conference (ECC'19)*, IFAC and IEEE, Naples, Italy."
publication_short = "In ECC'19"

# Abstract.
abstract = "Today, various nonlinear programming problem (NLP) solvers and C/C++ code generation frameworks are available as open source for solving nonlinear model predictive control (NMPC). Almost all the solvers are written in C/C++ code which are more compatible for the PC-based simulation environment. These codes are not directly compatible for embedded implementation and real-time control. An attempt has been made to address this shortcoming by creating a customized framework on top of the C code generated from Acado to make it directly compatible with ARM based embedded platforms. The study also analyzes the embedded implementation aspects using C code generated for qpOASES, qpDUNES, and HPMPC solvers from Acado. We show the results of hardware-in-loop (HIL) simulations with detailed analysis and comparison of memory requirement and achievable sampling time for three benchmark dynamical systems on different embedded platforms viz ARM Cortex M3, PYNQ FPGA and Raspberry Pi. The results show that qpOASES outperforms as compared to the other two solvers when the computational time is of prime importance for small prediction horizon. Similarly, when there are limited on-chip memory resources, qpDUNES can prove beneficial."

# Summary. An optional shortened abstract.


# Digital Object Identifier (DOI)
doi = ""

# Is this a featured publication? (true/false)
featured = true

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
#   projects = ["internal-project"]

# Links (optional).
#url_pdf = ""
url_preprint = "https://saketadhau.netlify.com/publication/ecc/ecc.pdf"
#url_code = "#"
#url_dataset = "#"
#url_project = ""
#url_slides = "#"
#url_video = "#"
#url_poster = "#"
#url_source = "#"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#links = [{name = "Custom Link", url = "http://example.org"}]

# Does this page contain LaTeX math? (true/false)
math = true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = "HIL simulation results of NMPC implemented on PYNQ FPGA board"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Smart"
+++
