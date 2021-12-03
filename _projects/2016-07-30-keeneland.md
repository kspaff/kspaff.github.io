---
title: 'Keeneland'
subtitle: 'NSF Track 2D GPU Cluster'
date: 2016-07-30 00:00:00
description: One of the first large GPU clusters made widely available to NSF scientific computing users
featured_image: '/images/keeneland.png'
---

One of the most exciting hardware projects of the Future Technologies group at ORNL was Keeneland, one of the first large GPU clusters that was widely available to users of NSF's scientific computing resources.
I was fortunate to be involved in many of aspects of the project with a focus on benchmarking and maximizing application performance.

Here's the project's final summary from NSF news with the key numbers:

* Served 942 total users of KIDS and KFS for research, development and educational purposes
* Contributed to at least 367 publications, presentations, and other software artifacts
* Provided over 50 million CPU hours were used on KFS and over 10 million SUs were provided to XSEDE (equivalent to ~50 million SUs on a CPU-centric system)
* Averaged 81.2% GPU utilization over Keeneland’s Full Scale 2-year production run (all GPUs, 24h, 7d)
* Contributed to the development of many early software packages for GPU heterogeneous computing: [Scalable Heterogeneous Computing (SHOC) Benchmarks](https://github.com/vetter/shoc), MAGMA BLAS libraries, Ocelot emulator, and many others
* Provided Advanced Application Support that increased GPU and system utilization and assisted with application development for [BEAST](https://beast.community/)/Beagle, improved batch matrix multiplication, and improvements to many large-scale applications; and,
* Employed 10 staff members, four faculty members, and nearly 40 students and postdoctoral research associates.

The Keeneland Project was a five-year cooperative agreement awarded by the National Science Foundation (NSF) in 2009 for the deployment of an innovative high performance computing system in order to bring emerging architectures to the open science community. The Georgia Institute of Technology (Georgia Tech) and its partners - Oak Ridge National Lab, University of Tennessee-Knoxville, and the National Institute for Computational Sciences - managed the facility, performed education and outreach activities for advanced architectures, developed and deployed software tools for this emerging class of architectures to ensure productivity, and teamed with early adopters to map their applications to Keeneland architectures.

In 2010, the Keeneland project procured and deployed its initial delivery system (KIDS): a 201 Teraflop, 120-node HP SL390 system with 240 Intel Xeon CPUs and 360 NVIDIA Fermi graphics processors, with the nodes connected by an InfiniBand QDR network. KIDS was being used to develop programming tools and libraries in order to ensure that the project can productively accelerate important scientific and engineering applications. The system was also available to a select group of users to port and tune their codes to a scalable GPU-accelerated system. In the spring of 2012 KIDS was upgraded from NVIDIA M2070 to M2090 GPUs for total peak performance of 255 TFLOPS.

In October of 2012, the Keeneland Full Scale (KFS) system was accepted by the NSF and went into production. KFS was a 264-node cluster based on HP SL250 servers. Each node had 32 GB of host memory, two Intel Sandy Bridge CPU’s, three NVIDIA M2090 GPUs, and a Mellanox FDR InfiniBand interconnect. The total peak double precision performance was 615 TF.

For more, see [our article in IEEE Computing in Science and Engineering](https://www.computer.org/csdl/magazine/cs/2011/05/mcs2011050090/13rRUNvgyZp).

