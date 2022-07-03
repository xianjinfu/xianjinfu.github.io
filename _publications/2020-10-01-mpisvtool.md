---
title: "MPI-SV: A Symbolic Verifier for MPI Programs"
collection: publications
permalink: /publication/2020-10-01-mpisvtool
excerpt: 'MPI-SV tool paper'
date: 2020-10-01
venue: 'ICSE 2020'
paperurl: 'http://xianjinfu.github.io/files/icse-2020-demo.pdf'
citation: 'Z. Chen, H. Yu, X. Fu and J. Wang, "MPI-SV: A Symbolic Verifier for MPI Programs," 2020 IEEE/ACM 42nd International Conference on Software Engineering: Companion Proceedings (ICSE-Companion), 2020, pp. 93-96.<br> '
---
Message passing is the primary programming paradigm in high-performance computing. However, developing message passing programs is challenging due to the non-determinism caused by parallel execution and complex programming features such as non-deterministic communications and asynchrony. We present MPI-SV, a symbolic verifier for verifying the parallel C programs using message passing interface (MPI). MPI-SV combines symbolic execution and model checking in a synergistic manner to improve the scalability and enlarge the scope of verifiable properties. We have applied MPI-SV to real-world MPI C programs. The experimental results indicate that MPI-SV can, on average, achieve 19x speedups in verifying deadlock-freedom and 5x speedups in finding counter-examples. MPI-SV can be accessed at https://mpi-sv.github.io, and the demonstration video is at https://youtu.be/zzCY0CPDNCw.

[Download paper here](http://xianjinfu.github.io/files/icse-2020-demo.pdf)

Recommended citation: Z. Chen, H. Yu, X. Fu and J. Wang, "MPI-SV: A Symbolic Verifier for MPI Programs," 2020 IEEE/ACM 42nd International Conference on Software Engineering: Companion Proceedings (ICSE-Companion), 2020, pp. 93-96..