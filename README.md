# CloverLeaf_OpenMP_offload

This is an OpenMP offload version of CloverLeaf version 1.3 for GPUs (tested on AMD and Nvidia) ported from the OpenACC version.

# Compiling

In most cases one needs to load the appropriate modules (including those for the accelerator in question) and then:

```
make clean; make COMPILER=CRAY
```

or,

```
make clean; make COMPILER=PGI
```
