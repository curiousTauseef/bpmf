ROOT=../../../c++

CXX=mpicxx
CFLAGS+=-DBPMF_HYBRID_COMM -DBPMF_OMP_SCHED -DBPMF_PROFILING

# for openmp
CFLAGS+=-fopenmp

# for GPI2
LDFLAGS+=-lGPI2 -libverbs

include ../Makefile.common

