SRC := mcf.c mcfutil.c readmin.c implicit.c pstart.c output.c treeup.c pbla.c pflowup.c psimplex.c pbeampp.c spec_qsort/spec_qsort.c
SRC := $(addprefix src/, $(SRC))
CFLAGS := -Isrc/spec_qsort -DSPEC_AUTO_SUPPRESS_OPENMP -DSPEC_LP64 -DSPEC -DNDEBUG
LDFLAGS := -lm
BENCH := 605.mcf_s

include ../Makefile.config
