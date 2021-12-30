---
title: Intelligent GPS L1 LOS/Multipath/NLOS Classifiers Based on Correlator-,
  RINEX- and NMEA-Level Measurements
publication_types:
  - "2"
authors:
  - Jiang C
  - admin
publication_short: ""
abstract: This paper proposes to use a correlator-level global positioning
  system (GPS) line-of-sight/multipath/non-line-of-sight (LOS/MP/NLOS) signal
  reception classifier to improve positioning performance in an urban
  environment. Conventional LOS/MP/NLOS classifiers, referred to as national
  marine electronics association (NMEA)-level and receiver independent exchange
  format (RINEX)-level classifiers, are usually performed using attributes
  extracted from basic observables or measurements such as received signal
  strength, satellite elevation angle, code pseudorange, etc. The
  NMEA/RINEX-level classification rate is limited because the complex signal
  propagation in urban environment is not fully manifested in these end
  attributes. In this paper, LOS/MP/NLOS features were extracted at the baseband
  signal processing stage. Multicorrelator is implemented in a GPS
  software-defined receiver (SDR) and exploited to generate features from the
  autocorrelation function (ACF). A robust LOS/MP/NLOS classifier using a
  supervised machine learning algorithm, support vector machine (SVM), is then
  trained. It is also proposed that the Skymask and code pseudorange double
  difference observable are used to label the real signal type. Raw GPS
  intermediate frequency data were collected in urban areas in Hong Kong and
  were postprocessed using a self-developed SDR, which can easily output
  correlator-level LOS/MP/NLOS features. The SDR measurements were saved in the
  file with the format of NMEA and RINEX. A fair comparison among NMEA-, RINEX-,
  and correlator-level classifiers was then carried out on a common ground.
  Results show that the correlator-level classifier improves the metric of F1
  score by about 25% over the conventional NMEA- and RINEX-level classifiers for
  testing data collected at different places to that of training data. In
  addition to this finding, correlator-level classifier is found to be more
  feasible in practical applications due to its less dependency on surrounding
  scenarios compared with the NMEA/RINEX-level classifiers.
draft: false
featured: true
tags: []
slides: ""
url_pdf: ""
image:
  caption: "Image credit: [**GPS
    Solutions**](https://media.springernature.com/full/springer-static/image/ar\
    t%3A10.1007%2Fs10291-021-01101-6/MediaObjects/10291_2021_1101_Fig1_HTML.png\
    ?as=webp)"
  focal_point: ""
  preview_only: false
  filename: ""
summary: ""
url_dataset: ""
url_project: ""
url_source: ""
url_video: ""
author_notes:
  - Xu
  - B.
  - Jia
  - Q.
  - Luo
  - Y.
  - Hsu
  - L.-T.
doi: https://doi.org/10.3390/rs11161851
publication: Remote Sensing
projects: []
date: 2021-12-30T12:33:48.189Z
url_slides: ""
publishDate: 2017-01-01T00:00:00.000Z
url_poster: ""
url_code: ""
---
