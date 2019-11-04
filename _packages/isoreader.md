---
title: isoreader
layout: default
weight: 1
repo: isoreader
binder: binder
---

This package is intended as a unified one-stop command line interface to all common IRMS (isotope ratio mass spectrometry) file formats used in stable isotope geochemistry. It enables the reading and processing of stable isotope data directly from the data files and thus provides a foundational tool for platform-independent, efficient and reproducible data reduction. Although implemented in R, it provides easy export to Python using the shared R/Python feather file format. Due to the implementation following the example of tidyverse's readr, isoreader takes care of error catching to avoid pipeline breaks because of problems encountered in source data files. At present, it can read most Thermo dual inlet (.did, .caf) and continuous flow (.dxf, .cf) data files as well as Elementar continuous flow data archives (.iarc) and Nu dual inlet files (.txt) with additional extensions for other file formats in the works.
