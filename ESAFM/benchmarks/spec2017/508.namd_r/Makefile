SRC := Compute.C ComputeList.C ComputeNonbondedFEP.C \
	 ComputeNonbondedLES.C ComputeNonbondedPProf.C ComputeNonbondedStd.C \
	 ComputeNonbondedUtil.C LJTable.C Molecule.C Patch.C PatchList.C \
	 ResultSet.C SimParameters.C erf.C spec_namd.C
SRC := $(addprefix src/, $(SRC))
CFLAGS := -DNAMD_DISABLE_SSE -DSPEC_AUTO_SUPPRESS_OPENMP -DSPEC_LP64 -DSPEC -DNDEBUG
LDFLAGS := -lm
BENCH := 508.namd_r
include ../Makefile.config
