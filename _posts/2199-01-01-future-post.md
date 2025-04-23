---
title: 'SST-update'
date: 2025-04-23
permalink: /posts/2025/04/blog-post-4/
tags:
  - cool posts
  - category1
  - category2
---

# Daily OISST SST Update WPS
Like posted on WRF/MPAS Forum: *It is recommended to convert the files from NetCDF format, to intermediate format, instead of trying to convert them to grib2 format.*
<https://forum.mmm.ucar.edu/threads/re-enquiry-about-sst-update-in-wrf.8113/><br>

I recommend to use NCL Function **wrf_wps_write_int** to directly convert original SST (nc format) to intermediate files like SST:2020-01-01_00 etc.


This post will show up by default. To disable scheduling of future posts, edit `config.yml` and set `future: false`. 
