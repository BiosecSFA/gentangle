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
```
git clone --recursive https://github.com/BiosecSFA/gentangle.git
```

## License

GENTANGLE is distributed under the terms of the GNU Affero General Public License v3.0. 

All new contributions must be made under the Affero GPL (version 3.0 or higher) license.

See LICENSE, COPYRIGHT, and NOTICE for details.

SPDX-License-Identifier: AGPL-3.0-or-later

LLNL-CODE-845475
