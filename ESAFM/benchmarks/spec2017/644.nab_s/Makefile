SRC := nabmd.c sff.c nblist.c prm.c memutil.c molio.c molutil.c \
	 errormsg.c binpos.c rand2.c select_atoms.c reslib.c database.c \
	 traceback.c chirvol.c specrand/specrand.c regex-alpha/regcomp.c \
	 regex-alpha/regerror.c regex-alpha/regexec.c regex-alpha/regfree.c
SRC := $(addprefix src/, $(SRC))
CFLAGS := -Isrc/specrand -Isrc/regex-alpha -DNDEBUG -DNOPERFLIB -DNOREDUCE -DSPEC_LP64 -DSPEC -DNDEBUG
LDFLAGS := -lm
BENCH = 644.nab_s

include ../Makefile.config
