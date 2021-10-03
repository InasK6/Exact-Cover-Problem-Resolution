CC= mpicc
LDFLAGS= -Wall -Wextra

all: exact_cover_MPI exact_cover_MPI2 exact_cover_MPI_MSlave

exact_cover_MPI: exact_cover_MPI.c
	$(CC) -o $@  $<  $(LDFLAGS)

exact_cover_MPI2: exact_cover_MPI_2.c
	$(CC) -o $@  $<  $(LDFLAGS)

exact_cover_MPI_MSlave: exact_cover_MPI_MasterSlave.c
	$(CC) -o $@  $<  $(LDFLAGS)

clean:
	-rm -f exact_cover_MPI exact_cover_MPI2 exact_cover_MPI_MSlave

.PHONY: all clean
