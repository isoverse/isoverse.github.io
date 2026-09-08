---
title: isoexplorer
layout: default
status: current
weight: 3
repo: isoexplorer
supersedes: isoviewer
install: |
  # install the released version from CRAN
  install.packages("isoexplorer")
  # check/install the isoextract file reader used by isoreader2
  isoreader2::ir_check_isoextract()
---

This package provides graphical user interface (GUI) components to explore stable isotope data files read with [isoreader2](https://isoreader2.isoverse.org/). It ships ready-to-run explorer apps for continuous flow, dual inlet and scan data as well as file metadata, a **Show code** feature that writes out the [isoreader2](https://isoreader2.isoverse.org/) code to reproduce whatever you are currently looking at, and a set of composable [shiny](https://shiny.posit.co/) modules that can be recombined into your own applications. **isoexplorer** succeeds the [isoviewer](https://isoviewer.isoverse.org/) package.
