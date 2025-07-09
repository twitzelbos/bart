First build command, having disabled OMP
CC=gcc-15 MACPORTS=0 FFTW_BASE=/opt/homebrew/opt/fftw BLAS_BASE=/opt/homebrew/opt/openblas OMP=0 gmake
