#----- Modify CC and CFLAGS as appropriate in your environment
CC = gcc
CFLAGS = -O3 -fopenmp

LIB = -lm -lc

UNITFILES = 

#------------ EXECUTABLE FILES ---------------

histo_locks : histo_atomic.o $(UNITFILES)
	$(CC) $(CFLAGS) -o histo_atomic histo_atomic.o $(UNITFILES) $(LIB)

clean:
	rm -f histo_atomic *.o

histo_locks.o : histo_atomic.c
	$(CC) $(CFLAGS) -c histo_atomic.c $(INCLUDE) 


