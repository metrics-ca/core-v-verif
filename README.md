# core-v-verif
Functional verification project for the CORE-V family of RISC-V cores.

## NEWS UPDATES:
**2020-12-16**: The [cv32e40p_v1.0.0](https://github.com/openhwgroup/core-v-verif/releases/tag/22dc5fc) of core-v-verif is released.
This tag clones the v1.0.0 release of the CV32E40P CORE-V core and will allow you to reproduce the verification environment as it existed at `RTL Freeze`.
<br>
More news is available in the [archive](https://github.com/openhwgroup/core-v-verif/blob/master/NEWS_ARCHIVE.md).

## Getting Started
First, have a look at the [OpenHW Group's website](https://www.openhwgroup.org) to learn a bit more about who we are and what we are doing.  
<br>
Reading the [Verification Strategy](https://core-v-docs-verif-strat.readthedocs.io/en/latest/) is strongly recommended.

### Getting started with CV32E40P
If you want to run a simulation there are two options:
1. To run the CORE testbench, go to `cv32e40p/sim/core` and read the README.
2. To run the CV32E40P UVM environment, go to `cv32e40p/sim/uvmt` and read the README.

#### CV32E40P coverage data
The most recently published coverage report for the CV32E40P can be found [here](https://openhwgroup.github.io/core-v-verif/).

### Getting started with CVA6
To run CVA6 testbench, go to [cva6](cva6) directory and read the README.

## Directory Structure of this Repo
### bin
Various utilities for running tests and performing various verification-related activities in the core-v-verif repository.

### core-v-cores
Empty sub-directory into which the RTL from one or more of the [CORE-V-CORES](https://github.com/openhwgroup/core-v-cores) repositories is cloned.

### cv32e40p
Verification Environments, testbenches, testcases and simulation Makefiles for the CV32E40P core.

### cva6
Verification Environments, testbenches, testcases and simulation Makefiles for the CVA6 cores.

### docs
Source for GitHub Pages.
Contains a pointers to the [Verification Strategy document](https://core-v-docs-verif-strat.readthedocs.io/en/latest/), the [CORE-V-DOCS](https://github.com/openhwgroup/core-v-docs) repository, and available coverage reports.

### mk
Common simulation Makefiles that support testbenches for all CORE-V cores.

### lib
Common components for the all CORE-V verification environments.

### vendor_lib
Verification components supported by third-parties.

## Contributing
We highly appreciate community contributions. You can get a sense of our current needs by reviewing the GitHub
[projects](https://github.com/openhwgroup/core-v-verif/projects) associated with this repository.   Individual work-items
within a project are defined as [issues](https://github.com/openhwgroup/core-v-verif/issues) with a `task` label.
<br><br>To ease our work of reviewing your contributions, please:

* Review [CONTRIBUTING](https://github.com/openhwgroup/core-v-verif/blob/master/CONTRIBUTING.md).
* Split large contributions into smaller commits addressing individual changes or bug fixes.
Do not mix unrelated changes into the same commit!
* Write meaningful commit messages.
* If asked to modify your changes, do fixup your commits and rebase your branch to maintain a clean history.
