THIS PACKAGE IS PURELY EXPERIMENTAL
==========================

This Julia package is an extension to the [`ApproxFun`](https://github.com/dlfivefifty/ApproxFun.jl) package
using non-classical 1D orthogonal polynomials, and extending methodology to other domains in 2D and 3D,
in particular the Disk-Slice and Trapezium in 2D, and the Surface of a Spherical Cap in 3D space.

Orthogonal Polynomial Families
==============

Implements spectral methods for solving PDEs.
The methods result in matrix operators which are "banded-block-banded".

All implementations are experimental.

The Julia implementation requires ApproxFun:

        https://github.com/dlfivefifty/ApproxFun.jl

OrthogonalPolynomialFamilies - contains the framework for expanding functions and building operators on a given interval in 1D with a given weight function.

DiskSliceFamilies - contains the framework for expanding functions and building operators on a specified Disk-Slice in 2D

TrapeziumFamilies - contains the framework for expanding functions and building operators on a specified Trapezium in 2D

SphericalCapFamiles - contains the framework for expanding functions and building operators on a specified Spherical Cap Surface in 3D
