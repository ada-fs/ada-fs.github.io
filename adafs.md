---
layout: page
title: ADA-FS
permalink: /adafs/
---

# ADA-FS
### Advanced Data Placement via Ad-hoc File Systems at Extreme Scale

For future HPC systems, data management is an essential factor. The location of
data that is needed during a calculation plays a central role in increasing the
efficiency of HPC systems. While already efficient methods for reserving data
exist on the processor-level, access to the parallel file system is still a
bottleneck. The volume of data that is expected for the calculation within
future applications exceeds the capacity of the node-local storage and requires
the download of data from the parallel file system during the runtime of the
application.

In HPC file systems are usually a shared medium, which are used by many users in
parallel. Furthermore, the performance is limited by the interface between the
central file system and the compute nodes. Thus, for an application it is
currently not possible to predict the actual load on the file system
infrastructure and to optimize the I/O subsystem.

The project aims to improve I/O performance for highly-parallel applications by
distributed ad-hoc overlay file systems. For this purpose, it examines how
job-specific temporary file systems can be efficiently provided for HPC
environments. These file systems are to be created from the resources of the
computing nodes involved. These temporary file systems are filled with the
necessary data through an integration into the scheduling system of the
supercomputer before the job starts. After the completion of the job, the data
is migrated back into the global parallel file system. The research approach
includes both the design of the file system itself as well as the questions
about the proper scheduling strategy for planning the necessary I/O transfers.

See ADA-FS on [sppexa.de](http://www.sppexa.de/general-information/projects-phase-2.html#ADAFS2).
