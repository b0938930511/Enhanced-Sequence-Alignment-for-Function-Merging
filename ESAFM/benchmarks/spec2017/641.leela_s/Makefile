SRC := FullBoard.cpp KoState.cpp Playout.cpp TimeControl.cpp \
	 UCTSearch.cpp GameState.cpp Leela.cpp SGFParser.cpp Timing.cpp Utils.cpp \
	 FastBoard.cpp Matcher.cpp SGFTree.cpp TTable.cpp Zobrist.cpp \
	 FastState.cpp GTP.cpp MCOTable.cpp Random.cpp SMP.cpp UCTNode.cpp
SRC := $(addprefix src/, $(SRC))
CFLAGS := -Isrc/ -DSPEC_LP64 -DSPEC -DNDEBUG
LDFLAGS := -lm
BENCH = 641.leela_s
include ../Makefile.config
