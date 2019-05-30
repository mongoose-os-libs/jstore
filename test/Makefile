all: test

REPO ?= $(HOME)/src/cesanta.com
CFLAGS ?= -Wall -Werror -Wno-missing-braces -O2
INC = -I. -I../src -I../include -I$(REPO) -I$(REPO)/frozen
SOURCES = jstore_test.c ../src/mgos_jstore.c \
					$(REPO)/common/cs_file.c \
					$(REPO)/common/cs_dbg.c \
					$(REPO)/common/str_util.c \
					$(REPO)/frozen/frozen.c \
					$(REPO)/common/mg_str.c \

test:
	cc $(CFLAGS) $(INC) $(SOURCES) -o /tmp/jt && /tmp/jt
