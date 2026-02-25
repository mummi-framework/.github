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

#### Publications

The MuMMI framework is described in the following publications. Please make appropriate
citations to relevant papers.

##### Workflow

1. Bhatia et al. <b>Generalizable Coordination of Large Multiscale Ensembles: Challenges and Learnings at Scale</b>.
   In Proceedings of the ACM/IEEE International Conference for High Performance Computing, Networking, Storage and Analysis, SC '21,
   Article No. 10, November 2021.
   [doi:10.1145/3458817.3476210](https://doi.org/10.1145/3458817.3476210).

2. Di Natale et al. <b>A Massively Parallel Infrastructure for Adaptive Multiscale Simulations: Modeling RAS Initiation Pathway for Cancer</b>.
   In Proceedings of the ACM/IEEE International Conference for High Performance Computing, Networking, Storage and Analysis, SC '19, Article No. 57, November 2019.
   [doi:10.1145/3295500.3356197](https://doi.org/10.1145/3295500.3356197).
   <br/><b><i>Best Paper at SC 2019</i></b>.

##### Overall framework and Biology Results

3. Ingólfsson et al. <b>Machine Learning-driven Multiscale Modeling Reveals Lipid-Dependent Dynamics of RAS Signaling Protein</b>.
   Proceedings of the National Academy of Sciences (PNAS),  vol. 119, issue 1, number e2113297119. 2022.
   [doi:10.1073/pnas.2113297119](https://doi.org/10.1073/pnas.2113297119).

4. Ingólfsson et al. <b>Machine Learning-driven Multiscale Modeling, bridging the scales with a next generation simulation infrastructure</b>.
  Under review, 2022.

##### Individual components (ML, simulations, transformations, etc.)

5. Bhatia et al. <b>Machine Learning Based Dynamic-Importance Sampling for Adaptive Multiscale Simulations</b>.
    Nature Machine Intelligence, vol. 3, pp. 401–409, May 2021.
    [doi:10.1038/s42256-021-00327-w](https://doi.org/10.1038/s42256-021-00327-w).

6. Zhang et al. <b>ddcMD: A fully GPU-accelerated molecular dynamics program for the Martini force field</b>. Journal of Chemical Physics, vol. 153, issue 4, 2021.
  [doi:10.1063/5.0014500](https://doi.org/10.1063/5.0014500).

7. Bhatia et al. <b>A Biology-Informed Similarity Metric for Simulated Patches of Human Cell Membrane</b>.
      Under Review, 2022.

8. Stanton et al. <b>Dynamic Density Functional Theory of Multicomponent Cellular Membranes</b>. Under Review, 2022. Available on [arXiv](https://arxiv.org/abs/2112.08651v1).

9. López et al. <b>Asynchronous Reciprocal Coupling of Martini 2.2 Coarse-Grained and CHARMM36 All-Atom Simulations in an Automated Multiscale Framework</b>.
    Under Review, 2022.

10. Nguyen et al. <b>Exploring CRD mobility during RAS/RAF engagement at the membrane</b>.
    Under Review, 2022.

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
