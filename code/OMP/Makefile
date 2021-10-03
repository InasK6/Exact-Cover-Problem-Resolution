CC= gcc
LDFLAGS= -fopenmp -Wall -Wextra

all: exact_cover_OMP  exact_cover_OMP1 exact_cover_OMP2

exact_cover_OMP: exact_cover_OMP.c
	$(CC)  -o $@  $<  $(LDFLAGS)

exact_cover_OMP1: exact_cover_OMP1.c
	$(CC) -o $@  $<  $(LDFLAGS)

exact_cover_OMP2: exact_cover_OMP2.c
	$(CC) -g -o $@  $<  $(LDFLAGS)

clean:
	-rm -f exact_cover_OMP exact_cover_OMP1 exact_cover_OMP2 

.PHONY: all clean


