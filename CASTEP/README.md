CASTEP
======

This folder contains files and documentation for building CASTEP on various HPC facilities.

History
-------

Date | Person | System | Version | Notes
---- | -------|--------|---------|------
2018-08-09 | Andy Turner | Isambard (GW4) | 18.1.0, Cray CCE 8 MPI, Arm ThunderX2 | MPI build instructions for Cirrus
2018-05-08 | Andy Turner | Cirrus (EPCC) | 16.1.1, Intel 17 MPI, Intel Broadwell | MPI build instructions for Cirrus
2018-01-19 | Andy Turner | Athena (HPC Mid+) | 18.1.0, GCC 6.x, MPI, Intel Broadwell | MPI build instructions for Athena
2018-01-19 | Andy Turner | ARCHER (EPCC) | 18.1.0, GCC 6.x, MPI, Intel Ivy Bridge | MPI build instructions for ARCHER
2017-11-30 | Andy Turner | Peta4-Skylake (Cambridge) | 16.1.2, Intel 17, Intel Skylake Gold | MPI build instructions for CSD3 Skylake
2017-01-05 | Andy Turner | ARCHER (EPCC) | 16.1.2, Intel 16, Serial, Intel x86_64 | Serial build instructions for ARCHER PP nodes using Intel 16 compilers
2016-12-21 | Andy Turner | ARCHER (EPCC) | 16.1.2, Intel 16, MPI, Intel Ivy Bridge | MPI build instructions for ARCHER Ivy Bridge nodes using Intel 16 compilers

Build Instructions
------------------

* [CASTEP 18.1.0 Isambard (Cavium ThunderX2, Arm, Cray XC50) CCE 8.x Build Instructions](Isambard_18.1.0_cce8_mpich3.md)
* [CASTEP 16.1.1 Cirrus (Intel Xeon Broadwell, HPE/SGI Apollo 8600) Intel 17 Build Instructions](Cirrus_16.1.1_intel17_HPEMPT.md)
* [CASTEP 18.1.0 Athena HPC Mid+ (Intel Xeon Broadwell, Huawei) GCC 6.x Build Instructions](Athena_18.1.0_gcc6_IMPI.md)
* [CASTEP 18.1.0 ARCHER (Intel Xeon Ivy Bridge, Cray XC30) GCC 6.x Build Instructions](ARCHER_18.1.0_gcc6_CrayMPT.md)
* [CASTEP 17.2.1 CSD3-Skylake (Intel Xeon Skylake Gold) Intel 17 Build Instructions](CSD3Skylake_17.2.1_intel17_IMPI.md)
* [CASTEP 16.1.2 ARCHER (Intel Xeon Ivy Bridge, Cray XC30) Intel 16 Build Instructions](ARCHER_16.1.2_intel16_CrayMPT.md)
* [CASTEP 16.1.2 ARCHER (Intel Xeon Ivy Bridge, Cray XC30) serial x86_64 Intel 16 Build Instructions](ARCHER_16.1.2_serial_intel16.md)

Notes
-----

* ARCHER serial versions are compiled to work on post-processing nodes, login nodes and compute nodes
* ARCHER MPI versions are compiled to work on compute nodes only

