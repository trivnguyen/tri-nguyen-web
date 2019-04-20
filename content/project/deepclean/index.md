+++
# Project title
title = "DeepClean" 
subtitle = "A Noise Regression Framework for GW detectors"

# Date this page was created
date = 2019-04-16T00:00:00

# Project summary to display on homepage
summary = "Using LSTM network to learn and subtract non-linear noise in GW detectors."

# Tags: can be used for filtering projects.
tags = ["Gravitational Waves", "Machine Learning", "LIGO", "Detector Characterization", "LSTM"]

# Optional external URL for project (replaces project detail page).
# external link = "http://example.org"
url_pdf = "deepclean.pdf"
url_code = "https://git.ligo.org/rich.ormiston/DeepClean"

# Featured image

[image]
    caption = "Schematic of LIGO interferometer design. Source: [LIGO](https://arxiv.org/abs/1602.03837)"

    # Focal point (optional)
    # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
    focal_point = "Smart"

+++

The Laser Interferometer Gravitational-Wave Observatory (LIGO) detects GWs by measuring the 
induced differential arm length between its two perpendicular arms. Since its sensitivity upgrade 
in 2016, LIGO has successfully detected many GW sources from black-hole to neutron-star mergers. However,
due to a number of noise sources, the detectors are currently operating below their design sensitivity.
These sources are instrumental and environmental effects, each coupling to the signal via a different 
(both linear and non-linear) mechanism.

LIGO currently relies on the Wiener filter to remove noise sources. However, the Wiener filter fails
to remove the non-linear contributions. Characterizing these non-linear contributions and removing them 
using standard statistical and signal processing techniques can be challenging if not impossible because the 
mechanisms are often complex and involved multiple noise channels. In this study, we use a machine learning 
algorithm called the Long Short-Term Memory neural network to learn and filter out these non-linear noise sources.

I first got involved in this project as a SURF student at LIGO Caltech in the summer of 2018, and have been continued 
it since. DeepClean, our noise regression framework, is currently being developed by me, my mentor 
[Michael Coughlin](https://www.michaelwcoughlin.com/), and co-mentor 
[Rich Ormiston](https://www.physics.umn.edu/people/ormiston.html). I developed the Tensorflow frontend/backend 
and the Bayesian hyperparameter framework for DeepClean.

For my SURF final report, please click [here](deepclean.pdf).

For DeepClean repository (may require LIGO authentification), please click [here]($url_code).

























