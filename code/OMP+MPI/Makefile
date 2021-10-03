CC= mpicc
LDFLAGS= -Wall -Wextra -fopenmp

all: exact_cover_MPI_OMP

exact_cover_MPI_OMP: exact_cover_MPIOMP.c
	$(CC) -o $@  $<  $(LDFLAGS)

clean:
	-rm -f exact_cover_MPI_OMP

.PHONY: all clean
