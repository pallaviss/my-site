+++
# Project title.
title = "X-ray tube detector alignment"

# Date this page was created.
date = 2016-04-27T00:00:00

# Project summary to display on homepage.
summary = "X=ray tube and digital detector alignment using UWB and IMU"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["x-ray"]

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
url_pdf = ""
url_slides = ""
url_video = ""
url_code = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# links = [{icon_pack = "fab", icon="twitter", name="Follow", url = "https://twitter.com/georgecushen"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your project's folder. 
#[image]
  # Caption (optional)
#  caption = "Photo by rawpixel on Unsplash"
  
  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Smart"
+++

In advanced mobile X-ray machines also referred to as ’radiology room on wheels’, the traditional cassettes have been replaced by modern wireless detectors. These detectors are randomly placed behind the patients. The misaligned placement of detector w.r.t X-ray tube can cause reshoots due to missing anatomies. Considering ALARA, this paper provides a novel method of alignment technique by combining the incoming real time data from the Ultrawideband sensor and Inertial Motion Unit sensor to calculate a very accurate position of the detector using tri-alteration algorithm and orientation w.r.t X-ray tube. It will reduce the time required for the X-ray tube repositioning and realignment, resulting in smooth user experience. The alignment is done by referring to the GUI provided and the coordinates can be read from LCD continuously.