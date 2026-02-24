# UKNNSS-Benchmarks

This page provides links to documentation and resources associated with benchmarks for
the UK NNSS procurement process. 

The benchmarks will play a key role in the procurement process and span full application 
benchmarks to synthetic micro-benchmarks. Please ensure you read the benchmark descriptions
carefully to understand the rules around source code modification, mandatory runtime 
configuration and options and the data that needs to be submitted at various stages in 
the procurement process.

This page and the benchmark descriptions will be maintained and updated throughout the
procurement process. Updates will be recorded in the [CHANGELOG](CHANGELOG.md).

## Application Benchmarks

The application benchmarks have been chosen to exercise a range of system requirements
and technical charateristics in areas of key importance to the UK research community.

- [CP2K](https://github.com/UKNNSS-Benchmarks/uknnss-benchmark-cp2k)
- DOLFINx
- [Grid](https://github.com/UKNNSS-Benchmarks/uknnss-benchmark-grid)
- [LAMMPS](https://github.com/UKNNSS-Benchmarks/uknnss-benchmark-lammps)

## IO Benchmarks

The IO benchmarks are designed to be easily executed tests that provide a way
compare the performance of the parallel file system(s) that are included in
the procurement on a range of different metrics and IO patterns.

- [IOR/MDTEST](https://github.com/UKNNSS-Benchmarks/uknnss-benchmark-ior_mdtest): test IO read/write bandwidth and metadata performance
- [Pynamic](https://github.com/UKNNSS-Benchmarks/uknnss-benchmark-pynamic): test Python module import performance

## Synthetic Micro-benchmarks

The synthetic micro-benchmarks are a set of simple to build and execute tests that
compare key technical features of the systems in a consistent way. See the individual
test descriptions for detail on the requirements.

- [BabelStream](https://github.com/UKNNSS-Benchmarks/uknnss-benchmark-babelstream): evaluate memory bandwidth
- [OSU MPI Micro Benchmarks](https://github.com/UKNNSS-Benchmarks/uknnss-benchmark-omb): evaluate MPI point to point and collective performance
- [ziatest](https://github.com/UKNNSS-Benchmarks/uknnss-benchmark-ziatest): evaluate MPI startup time
- [HPL](https://github.com/UKNNSS-Benchmarks/uknnss-benchmark-hpl): evaluate FP64 performance
- [HPCG](http://github.com/UKNNSS-Benchmarks/uknnss-benchmark-hpcg): evaluate performance balance between memory access and FP64


