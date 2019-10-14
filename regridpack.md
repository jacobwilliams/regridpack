project: regridpack
project_dir: ./src
output_dir: ./doc
project_github: https://github.com/jacobwilliams/regridpack
summary: Modern Fortran Edition of REGRIDPACK
author: Jacob Williams
github: https://github.com/jacobwilliams
predocmark_alt: >
predocmark: <
docmark_alt:
docmark: !
display: public
         private
         protected
source: true
graph: false
extra_mods: iso_fortran_env:https://gcc.gnu.org/onlinedocs/gfortran/ISO_005fFORTRAN_005fENV.html
exclude: regridpack_test.f90

Brief description
---------------

This is an updated and modernized version of REGRIDPACK, a suite of Fortran routines
for interpolating values between one-, two-, three-, and four-dimensional arrays defined
on uniform or nonuniform orthogonal grids. This operation is commonly referred to as "regridding."
Linear or cubic interpolation can be selected independently in each dimension.
Extrapolation is not allowed. The subroutines in REGRIDPACK cannot be used to
transfer values on nonorthogonal (randomly scattered) data grids.

# License

The regridpack source code and related files and documentation are distributed under a permissive free software [license](https://github.com/jacobwilliams/regridpack/blob/master/LICENSE.txt) (BSD-style).
