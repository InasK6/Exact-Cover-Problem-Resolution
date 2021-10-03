CC= gcc
LDFLAGS= -Wall -Wextra

all: exact_cover

exact_cover: exact_cover.c
	 $(CC) -o $@ $< $(LDFLAGS)

clean:
	-rm -f  exact_cover

.PHONY: all clean

