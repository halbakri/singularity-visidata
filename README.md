![Status](https://github.com/pscedu/singularity-visidata/actions/workflows/main.yml/badge.svg)
![Issue](https://img.shields.io/github/issues/pscedu/singularity-visidata)
![forks](https://img.shields.io/github/forks/pscedu/singularity-visidata)
![Stars](https://img.shields.io/github/stars/pscedu/singularity-visidata)
![License](https://img.shields.io/github/license/pscedu/singularity-visidata)

# singularity-visidata
![Example](https://camo.githubusercontent.com/5c819cd018e8bb6569076a3ea712b322495917070496b1313b9a979b0c4108a6/687474703a2f2f76697369646174612e6f72672f667265712d6d6f76652d726f772e676966)
Singularity recipe for [visidata](https://www.visidata.org/).

## Installing the container on Bridges 2
Copy the

* `SIF` file
* and the `aws` and `aws_completer` script

to `/opt/packages/visidata/2.4`.

Copy the file `modulefile.lua` to `/opt/modulefiles/visidata` as `2.4.lua`.

## Building the image using the recipe

### To build the image locally
Run the script `build.sh` to build image locally.

```
bash ./build.sh
```

### To build the image remotely
Run the script `rbuild.sh` to build image remotely.

```
bash ./rbuild.sh
```

## To run tests
To run the available tests, run the command

```
bash ./test.sh
```

---
Copyright © 2020-2021 Pittsburgh Supercomputing Center. All Rights Reserved.

The [Biomedical Applications Group](https://www.psc.edu/biomedical-applications/) at the [Pittsburgh Supercomputing Center](http://www.psc.edu) in the [Mellon College of Science](https://www.cmu.edu/mcs/) at [Carnegie Mellon University](http://www.cmu.edu).
