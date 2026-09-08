---
title: isoreader
layout: default
status: older
weight: 5
repo: isoreader
superseded_by: isoreader2
---

This package is a unified one-stop command line interface to all common IRMS (isotope ratio mass spectrometry) file formats used in stable isotope geochemistry. It enables the reading and processing of stable isotope data directly from the data files and thus provides a foundational tool for platform-independent, efficient and reproducible data reduction. Due to the implementation following the example of tidyverse's readr, isoreader takes care of error catching to avoid pipeline breaks because of problems encountered in source data files. It can read most Thermo dual inlet (`.did`, `.caf`), continuous flow (`.dxf`, `.cf`) and scan (`.scn`) data files as well as Elementar continuous flow data archives (`.iarc`) and Nu dual inlet files (`.txt`).
