---
title: "FSE migration tools"
date: 2017-01-05
weight: 5
description: >
 We keep the majority of our data migration tools in the open, and we welcome both use and contributions.
---
# Introduction
On the [FSE Github organization](https://github.com/FOLIO-FSE), you will find a couple of repositories that together help form the 
data migration processes that is used by FSE.

For details on the migration processes in various areas, head over to the sections in the menue on the left.

# Requirements and installation
## All built on Python 3
All tools are written in Python 3, and requires Python 3.7 to run.
## Platforms
We typically run these tools on Linux in either WSL or on AWS, but other platforms should work just as well. The UI parts of [service_tools](https://github.com/FOLIO-FSE) built on [Gooey](https://github.com/chriskiehl/Gooey) should also work on most platforms.

We use pipenv for managing virtual environments and Python packages in one place. There are no requirements.txt files, so you will need to install any missing packages one by one

# Contributions
We are happy for any contributions in all areas. If you find something that needs fixing, just let us know via the issue tracker on Github or just get in touch.