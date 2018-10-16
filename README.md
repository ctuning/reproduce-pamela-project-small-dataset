[![compatibility](https://github.com/ctuning/ck-guide-images/blob/master/ck-compatible.svg)](https://github.com/ctuning/ck)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](http://creativecommons.org/licenses/by/4.0/)

CK repository with medium data set (20 frames) for the CK-powered SLAMbench
===========================================================================

Supporting data sets in the [Collective Knowledge format (CK)]
to be easily plugged in to the [CK-based research workflows for SLAMBench](https://github.com/ctuning/reproduce-pamela-project)

Minimal CK installation
=======================

The minimal installation requires:

* Python 2.7 or 3.3+ (limitation is mainly due to unitests)
* Git command line client.

### Linux/MacOS

You can install CK in your local user space as follows:

```
$ git clone http://github.com/ctuning/ck
$ export PATH=$PWD/ck/bin:$PATH
$ export PYTHONPATH=$PWD/ck:$PYTHONPATH
```

You can also install CK via PIP with sudo to avoid setting up environment variables yourself:

```
$ sudo pip install ck
```

### Windows

First you need to download and install a few dependencies from the following sites:

* Git: https://git-for-windows.github.io
* Minimal Python: https://www.python.org/downloads/windows

You can then install CK as follows:
```
 $ pip install ck
```

or


```
 $ git clone https://github.com/ctuning/ck.git ck-master
 $ set PATH={CURRENT PATH}\ck-master\bin;%PATH%
 $ set PYTHONPATH={CURRENT PATH}\ck-master;%PYTHONPATH%
```

CK workflow installation for SLAMBench (PAMELA project)
=======================================================

```
$ ck pull repo:reproduce-pamela-project
$ ck pull repo:reproduce-pamela-project-medium-dataset
```

See [ck-slambench](https://github.com/ctuning/reproduce-pamela-project) for more info.

Support
=======
The [non-profit cTuning foundation (France)](http://cTuning.org)
and [dividiti Ltd (UK/US)](http://dividiti.com)
help academic and industrial projects to use
[Collective Knowledge framework (CK)](http://cKnowledge.org) and implement sustainable
and portable research software, share artifacts and workflows as reusable and
customizable components, crowdsource and reproduce experiments,
enable [collaborative AI/SW/HW co-design from IoT to supercomputers](http://cKnowledge.org/ai)
to trade-off speed, accuracy, energy, size and costs,
accelerate knowledge discovery, and facilitate technology transfer.
Contact [them](mailto:grigori.fursin@ctuning.org;anton@dividiti.com) 
for further details.

