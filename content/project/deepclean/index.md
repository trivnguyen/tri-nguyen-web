+++
# Project title
title = "DeepClean" 
subtitle = "A Noise Regression Framework for GW detectors"

# Date this page was created
date = 2019-04-16T00:00:00

# Project summary to display on homepage
summary = "Using LSTM network to learn and subtract non-linear noise in GW detectors."

# Tags: can be used for filtering projects.
tags = ["Gravitational Waves", "Machine Learning", "LIGO", "Detector Characterization", "Neural Network", "LSTM"]

# Optional external URL for project (replaces project detail page).
# external link = "http://example.org"

# Featured image

[image]
    caption = "PSD after DeepClean subtracts the beam jitter noise in LHO O1 data."

    # Focal point (optional)
    # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
    focal_point = "Smart"

+++

[Deep Clean](deepclean.pdf)

This is my project for LIGO SURF Summer 2018.

**Abstract**: We apply long short-term memory (LSTM) neural networks as a time-series regression analysis technique to filter instrumental noises from gravitational-wave detectors at the Laser Interferometer Gravitational-Wave Observatory (LIGO). Unlike traditional neural networks, LSTM networks store and use information from their past inputs, thus robust in handling sequential data like gravitational-wave signals. Once trained, an LSTM network should be able to learn, predict, and subtract both the linear and non-linear noise coupling mechanisms, given there exist a set of witness channels monitoring these noises. The result would improve LIGO's sensitivity, most greatly at the low-frequency limit 20-100 Hz where noise features are expected to be easier to learn, and allow the detection of gravitational-wave sources currently below the noise floor.






