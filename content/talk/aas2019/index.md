+++
title = "Extending the reach of gravitational-wave detectors with machine learning"

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date = 2019-01-18T10:40:00
#date_end = 2019-04-19T10:14:59-04:00
all_day = false

# Schedule page publish date (NOT talk date).
publishDate = 2019-04-19T10:14:59-04:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Tri Nguyen"]

# Location of event.
location = "Seattle, WA"

# Name of event and optional event URL.
event = "American Astronomical Society"
event_url = "https://aas.org/meetings/aas233"

# Abstract. What's your talk about?
abstract = "Since the sensitivity upgrade in 2015, the Laser Interferometer Gravitational-wave Observatory (LIGO) has detected a number of black-hole and neutron star mergers. However, since strong sources of gravitational waves (GWs) produce a typical displacement of about 10-18 m (about 1000 times smaller than the diameter of a proton), techniques to reduce and filter instrumental and environmental noise have become increasingly important for the detection of weaker and more distant sources. Our group applied the Long Short-Term Memory (LSTM) neural network model, a subset of machine learning algorithms (MLAs), to noise regression analysis at LIGO. We used LSTMs because they are robust in handling sequential data. Given the time series from the GW and witness channels, the network predicts and subsequently subtracts background noise over a frequency band. Furthermore, unlike the current noise filtering technique, the Wiener filter, non-parametric MLAs like LSTMs, once trained, are capable of learning both the linear and nonlinear noise coupling mechanisms. For the linear contribution, the network matches the subtraction power of the Wiener filter. For the nonlinear contribution, the network performs well on generated mock data. Our framework is generic enough to be applied to a wide variety of series regression problems in many areas of science."

# Summary. An optional shortened abstract.
summary = ""

# Is this a featured talk? (true/false)
featured = true

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Gravitational Waves", "LIGO", "LSTM", "Machine Learning", "Detector Characterization", "Caltech SURF", "AAS"]

# Markdown Slides (optional).
#   Associate this page with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Optional filename of your slides within your talk folder or a URL.
url_slides = "talk.pdf"

# Projects (optional).
#   Associate this talk with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = ["deepclean"]

# Links (optional).
url_pdf = ""
url_video = ""
url_code = ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
