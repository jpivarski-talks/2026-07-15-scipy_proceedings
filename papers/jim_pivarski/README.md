---
abstract: |
  The University of Chicago's Data Science Institute (DSI) works with 11th Hour
  Project grantees to support environmental and human rights work. In this paper,
  we describe a collaboration with the Occidental Arts & Ecology Center (OAEC)
  on their Fuels-to-Flows program, which stabilizes upland waterways by adding
  brushwood that would otherwise fuel forest fires. Gullies are hidden by trees,
  so we used publicly available, sub-meter resolution LiDAR data to identify
  gullies by the shape of the landscape throughout Sonoma County, California. Due
  to the limited size of hand-labeled training datasets, we built an alternative
  to a Convolutional Neural Network (CNN) by engineering convolutional kernels
  using domain-specific knowledge---a "right-sized machine learning" solution for
  this problem---then identified gully centerlines and built a network of gullies
  as paths. The final deliverable is a statically hosted map application that puts
  all available information into the hands of restoration practitioners and land
  managers: the gully network, forest fire fuel proxies, aerial imagery, elevation
  contours, cross-sectional profiling tools, and differences in elevation between
  two LiDAR scans in 2013 and 2022. In this paper, we also describe how we
  overcame technological problems: CUDA programming in Python using Numba to
  handle our unusually large convolution kernels, PMTiles to serve hundreds of
  gigabytes of map data as a static website, and cross-sectional profiling tools.
---
