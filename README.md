---
x-masysma-name: ssd-optimization
section: 32
title: MDVL SSD Optimization
author: ["Linux-Fan, Ma_Sys.ma (Ma_Sys.ma@web.de)"]
keywords: ["mdvl", "ssd", "cron"]
date: 2020/02/17 13:23:43
lang: en-US
x-masysma-repository: https://www.github.com/m7a/lp-ssd-optimization
x-masysma-website: https://masysma.lima-city.de/32/mdvl-ssd-optimization.xhtml
x-masysma-owned: 1
x-masysma-copyright: |
  Copyright (c) 2020 Ma_Sys.ma.
  For further info send an e-mail to Ma_Sys.ma@web.de.
---
Description
===========

This package provides script `fstrim` as an automatically called cronjob to run
once per week. It invokes the necessary trim operations for SSD devices and is
thus expected to be installed on all SSD-enabled systems.

See <https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=767194> for further
details.

To build the package, use `ant package`.
