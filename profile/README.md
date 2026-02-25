# Multiscale Machine-Learned Modeling Infrastructure (MuMMI)

MuMMI was developed as part of the **Pilot2** project of the
[Joint Design of Advanced Computing Solutions for Cancer](https://cbiit.cancer.gov/ncip/hpc/jdacs4c) and the [ADMIRRAL](https://computational.cancer.gov/about/admirral) project both
funded jointly by the [Department of Energy](http://www.doe.gov) (DOE) and the [National Cancer Institute](http://www.cancer.gov) (NCI).
ADMIRRAL is the follow-up project for Pilot 2.

The ADMIRRAL/Pilot 2 project focuses on developing multiscale simulation models for
understanding the interactions of the lipid plasma membrane with the [RAS and RAF](https://www.cancer.gov/research/key-initiatives/ras)
proteins. The broad computational tool development aims of this pilot are:
* Developing scalable multi-scale molecular dynamics code that will automatically switch between continuum, coarse-grained and all-atom simulations.
* Developing scalable machine learning and predictive models of molecular simulations to:
    * identify and quantify states from simulations
    * identify events from simulations that can automatically signal change of resolution between continuum, coarse-grained and all-atom simulations
    * aggregate information from the multi-resolution simulations to efficiently feedback to/from machine learning tools
* Integrate sparse information from experiments with simulation data.

#### Authors and Acknowledgements

MuMMI was initially funded by the Pilot 2 project led by Dr. Fred Streitz (DOE) and
Dr. Dwight Nissley (NIH). We acknowledge contributions from the entire
Pilot 2 team. After Pilot 2 ended, MuMMI was funded as part of the
Artificial-Intelligence-Driven Multiscale Investigation of the RAS/RAF Activation
Lifecycle ([ADMIRRAL](https://computational.cancer.gov/about/admirral)) project led by
Dr. Fred Streitz (DOE) and Dr. Dwight Nissley (NIH).

This work was performed under the auspices of the U.S. Department
of Energy (DOE) by Lawrence Livermore National Laboratory under Contract DE-AC52-07NA27344.

Contact: Lawrence Livermore National Laboratory, 7000 East Avenue, Livermore, CA 94550.

#### Contributing

Contributions may be made through pull requests and/or issues on github.

### License

MuMMI Core is distributed under the terms of the MIT License.
All new contributions must be made under the MIT license.

SPDX-License-Identifier: MIT

LLNL-CODE-2015414
