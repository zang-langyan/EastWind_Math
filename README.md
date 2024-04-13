# EastWind Math

## EastWind Math

It is a wrapper library of BLAS and LAPACK for the EastWind Engine Math support.

## EastWind Graphics

This submodule provides some utility functions for graphics computing using EastWind Math template class.

## Build
You would need a cmake version >= 3.20 and a c++ compiler and especially gfortran compiler to build this library
```shell
cmake -B build -DCMAKE_EXPORT_COMPILE_COMMANDS=1
cmake --build build
```

## Features
So far, this library supports the basic Vector and Matrix operations and LU decomposition for square matrix including inverse computation based on that.

## TODO List
- [ ] LU decomposition full support 
- [ ] Cholesky decomposition 
- [ ] QR decomposition
- [ ] SVD decomposition
        
