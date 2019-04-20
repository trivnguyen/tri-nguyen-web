+++
# Project title
title = "KITCAT"
subtitle = "Probing the large-scale structure of the Universe"

# Date this page was created
date = 2019-04-16T00:00:00

# Project summary to display on homepage
summary = "Accelerating the calculation of the galactic two-point correlation function with k-d tree."

# Tags: can be used for filtering projects.
tags = ["Cosmology", "Algorithm", "Two-point Correlation", "Baryon Acoustic Oscillation", "DESI", "SDSS", 
"BOSS", "Large-scale Structure"]

# Optional external URL for project (replaces project detail page).
# external link = "http://example.org"
url_code = "https://github.com/DESI-UR/KITCAT"

# Featured image

[image]
    caption = "Baryon acoustic oscillations are imprinted in the distribution of galaxies. Source: [SDSS](https://www.sdss.org/boss-3/)"

    # Focal point (optional)
    # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
    focal_point = "Smart"

+++

The early universe consists of a hot and dense photon-baryon plasma. Small density fluctuations in the plasma give
rise to acoustic sound waves. These sound waves are driven by radiation pressure and propagate at a relativistic
speed. About 400,000 years after the Big Bang, the universe is cool enough for free electrons to be captured 
by protons to form neutral hydrogen atoms. These newly-formed hydrogen atoms do not interact strongly with photons, and,
as a result, photons decouple from the matter. No longer supported by radiation pressure, the baryon sound waves
halt, producing density bumps, often called the baryon acoustic oscillations (BAOs), at about 150 Mpc detectable in 
the anisotropy of the cosmic microwave background (CMB) and in the distribution of galaxies. 

Because BAOs create an excess of galaxies at about 150 Mpc, they can be detected by studying at the large-scale clustering
of galaxies. To do this, physicists often use the spatial two-point correlation function (TPCF). The TPCF is a 
mathematical tool to contrast between the observed distribution of galaxies and the distribution in which all galaxies 
are uniformly distributed over the observed volume (referred to as the random distribution). It describes the excess 
probability (observed over random) of finding two galaxies separated by some separation variables 
(e.g. distance, angle). With this, BAOs should create a small bump in the spatial TPCF at about 150 Mpc.

KITCAT, short for the Kd-tree Implementation for Two-point Correlation AlgoriThm, is a simple and fast tool to compute
the 1-D and 2-D spatial TPCF of galaxies. By assuming the random distribution can be separated into angular variables 
(declination and right ascension) and redshift, KITCAT uses convolution of probability distributions to accelerate
the computation of the TPCF. Thanks to this, KITCAT also allows for a fast and flexible scan over the cosmological 
parameter space.

For more information, refer to [this paper](kitcat.pdf) on which KITCAT is based.

For KITCAT v2.0.0: [Github](https://github.com/DESI-UR/KITCAT), [Zenodo](https://doi.org/10.5281/zenodo.2640917)
