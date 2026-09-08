---
title: isoreader2
layout: default
status: current
weight: 1
repo: isoreader2
hex: isoreader
supersedes: isoreader
install: |
  # install the released version from CRAN
  install.packages("isoreader2")
  # check/install the isoextract file reader
  isoreader2::ir_check_isoextract()
---

This package provides easy access to the raw data and metadata stored in the file formats commonly encountered in scientific disciplines that make use of stable isotopes. It enables the reading and processing of stable isotope data directly from the data files and thus provides a foundational tool for platform-independent, efficient and reproducible data reduction. **isoreader2** succeeds the [isoreader](https://isoreader.isoverse.org/) package with a completely new architecture built around the [isoextract](https://github.com/isoverse/IsofileExtractor) command line tool, which makes it significantly faster and adds support for a wider range of file formats: Isodat continuous flow (`.dxf`, `.cf`), dual inlet (`.did`, `.caf`) and scan (`.scn`) files, Elementar IonOS (`.iarc`) and LyticOS (`.larc`) archives, SerCon Callisto (`.bch`) folders, and Thermo Qtegra (`.imexp`) notebooks. The extracted data comes with a consistent data structure and tools to aggregate, convert signal units, filter, and visualize the data.
