---
abstract: Non-line-of-sight (NLOS) global navigation satellite system (GNSS)
  signals are a major factor that limits the GNSS positioning accuracy in urban
  areas. An advanced GNSS signal processing technique, the vector tracking loop
  (VTL), has been applied to NLOS detection and correction, and its feasibility
  and superior performance have been reported in recent studies. In a VTL-based
  GNSS receiver, the navigation solutions (i.e., position, velocity and time
  (PVT)) are used to predict the signal tracking loop parameters. The difference
  between the predicted signal and the received signal within the code
  discriminator output can be used to detect NLOS reception. We generate the
  probability of NLOS detection by modeling the code discriminator outputs using
  Gaussian fitting. If this probability is larger than a predefined threshold,
  NLOS reception is deemed to occur. Then, the NLOS-induced pseudorange
  measurement bias is estimated as a state variable in the state vector, i.e.,
  an augmented state vector is created for the extended Kalman filter. Two GPS
  L1 C/A signal datasets from a static test and a dynamic test are investigated
  using the proposed algorithm. The experimental results indicate that when NLOS
  reception is present, the proposed approach outperforms the other two methods,
  i.e., the standard VTL method without considering NLOS reception and the
  VTL-based NLOS detection and correction method with multicorrelators, in terms
  of the positioning performance. In addition, the proposed approach has a lower
  computational load than the VTL method with multicorrelators.
slides: example
url_pdf: ""
publication_types:
  - "2"
authors:
  - Jiang
  - C
  - admin
author_notes:
  - First Author
  - Second Author
publication: In *GPS Solutions*
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere
  tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin
  condimentum.
url_dataset: ""
url_project: ""
publication_short: In *ICW*
url_source: ""
url_video: ""
title: Journal articles
doi: ""
featured: true
tags: []
projects:
  - example
image:
  caption: "Image credit:
    [**Unsplash**](https://media.springernature.com/full/springer-static/image/\
    art%3A10.1007%2Fs10291-021-01101-6/MediaObjects/10291_2021_1101_Fig1_HTML.p\
    ng?as=webp)"
  focal_point: ""
  preview_only: false
  filename: https://media.springernature.com/full/springer-static/image/art%3A10.1007%2Fs10291-021-01101-6/MediaObjects/10291_2021_1101_Fig1_HTML.png?as=webp
date: 2013-07-01T00:00:00Z
url_slides: ""
publishDate: 2017-01-01T00:00:00Z
url_poster: ""
url_code: ""
---
