SRC := attacks.cpp bitboard.cpp bits.cpp board.cpp draw.cpp endgame.cpp \
	 epd.cpp generate.cpp initp.cpp make.cpp moves.cpp neval.cpp pawn.cpp \
	 preproc.cpp search.cpp see.cpp sjeng.cpp state.cpp ttable.cpp utils.cpp
SRC := $(addprefix src/, $(SRC))
CFLAGS := -DBIG_MEMORY -DSPEC_LP64 -DSPEC -DNDEBUG
LDFLAGS := -lm
BENCH = 631.deepsjeng_s

include ../Makefile.config
