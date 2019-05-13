+++
# Project title.
title = "ECG on internet using Rasperry Pi"

# Date this page was created.
date = 2016-04-27T00:00:00

# Project summary to display on homepage.
summary = "Displays real time ECG on internet using Rasperry Pi"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["ECG"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Links (optional).
url_pdf = "https://ieeexplore.ieee.org/document/8668157"
url_slides = ""
url_video = ""
url_code = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#links = [{icon_pack = "fab", icon="twitter", name="Follow", url = "https://twitter.com/georgecushen"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your project's folder. 
#[image]
  # Caption (optional)
#  caption = "Photo by rawpixel on Unsplash"
  
  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Smart"
+++
The current status of heart disease in India is alarming, with projections suggesting that by the year 2020, the population of heart patients in India will surpass all the countries.Thus, monitoring the electrical activity of heart i.e. electrocardiogram is a necessity rather than luxury. ECG machines available in hospital are rather expensive. This paper aims at charting the ECG signal using the Raspberry Pi Arm processor. The ECG signals are recorded from the patient via the AD8232 ECG module and then this data is digitized using serial ADC MCP3008. The processor maps the signal on an online graphics tool plotl.ly using python programming. The main advantage of this system is that the result can be viewed at any place at any time. In this way, Internet of Things (IOT) concept is used to diagnose the heart defect and abnormalities in ECG without involving expensive ECG machines.
