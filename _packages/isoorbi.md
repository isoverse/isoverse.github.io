---
title: isoorbi
layout: default
status: current
weight: 4
repo: isoorbi
install: |
  # install the released version from CRAN
  install.packages("isoorbi")
  # check/install the isoraw file reader
  isoorbi::orbi_check_isoraw()
---

This package is intended for processing isotopocule measurements from an **Orbitrap Isotope Solutions** mass spectrometer. It reads the instrument's `.raw` files directly (recommended) as well as the `.isox` output created by IsoX (legacy approach), and provides pipelines for identifying isotopocules, flagging satellite peaks, defining base peaks, calculating isotopocule ratios, evaluating shot noise and drift, and visualizing raw data, spectra and results.
