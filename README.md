___
# GENTANGLE
## Integrated computational design of gene entanglements

**GENTANGLE (Gene Tuples ArraNGed in overLapping Elements) is a high performance containerized pipeline for the computational design of two overlapping genes translated in different reading frames of the genome that can be used to design and test gene entanglements for new microbial engineering projects using arbitrary sets of user specified gene pairs.**
___

## Introduction

The design of two overlapping genes in a microbial genome is an emerging technique for adding more reliable control mechanisms in engineered organisms for increased safety. The design of functional gene pairs is a challenging procedure and computational design tools are used to improve the efficiency to deploy successful designs in new genetically engineered systems. GENTANGLE provides an end-to-end computational solution for the design of these gene entanglements. 

In GENTANGLE, the entire sequence entanglement design process is automated and integrated into a high performance pipeline, and deployed using a single Singularity container to support portability and reproducible output. This container exposes several entry points following the Scientific Filesystem (SCIF) standard for encapsulating multiple applications into a single container.

The GENTANGLE pipeline is composed of three main components:
1) protein sequence preparation for fitness modeling,
2) protein fitness estimation and sequence entanglement search (CAMEOs eXtended aka CAMEOX), and
3) analysis and visualization of gene entanglement solutions.

## Installation
### GENTANGLE source code
GENTANGLE git repository includes several submodules, so please use the `--recursive` argument when cloning the repository:
```
git clone --recursive https://github.com/BiosecSFA/gentangle.git
```
### GENTANGLE Singularity container

You can download the image from [ftp://gdo-bioinformatics.ucllnl.org/gentangle/gentangle.sif](ftp://gdo-bioinformatics.ucllnl.org/gentangle/gentangle.sif) (anonymous ftp download supported). 

## Documentation

Please visit the [GENTANGLE wiki](https://github.com/BiosecSFA/gentangle/wiki) for updated documentation.

## License

GENTANGLE is distributed under the terms of the GNU Affero General Public License v3.0. 

All new contributions must be made under the Affero GPL (version 3.0 or higher) license.

See LICENSE, COPYRIGHT, and NOTICE for details.

SPDX-License-Identifier: AGPL-3.0-or-later

LLNL-CODE-845475

## Funding

This work is supported by the U.S. Department of Energy, Office of Science, Office of Biological and Environmental Research, Lawrence Livermore National Laboratory Secure Biosystems Design SFA “From Sequence to Cell to Population: Secure and Robust Biosystems Design for Environmental Microorganisms”.  Work at LLNL is performed under the auspices of the U.S. Department of Energy at Lawrence Livermore National Laboratory under Contract DE-AC52-07NA27344. 

___

If you use GENTANGLE in your research, please cite the following papers. Thanks!

 1. Martí, JM, _et al._ **GENTANGLE: integrated computational design of gene entanglements**. _In preparation_. 2023. 

 2. Blazejewski T, Ho HI, Wang HH. **Synthetic sequence entanglement augments stability and containment of genetic information in cells**. _Science_. 2019 Aug 9;365(6453):595-8. https://doi.org/10.1126/science.aav5477
___
