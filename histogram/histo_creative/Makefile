#----- Modify CC and CFLAGS as appropriate in your environment
CC = gcc
CFLAGS = -O3 -fopenmp

LIB = -lm -lc

UNITFILES = 

#------------ EXECUTABLE FILES ---------------

histo_creative : histo_creative.o $(UNITFILES)
	$(CC) $(CFLAGS) -o histo_creative histo_creative.o $(UNITFILES) $(LIB)

clean:
	rm -f histo_creative *.o

histo_creative.o : histo_creative.c
	$(CC) $(CFLAGS) -c histo_creative.c $(INCLUDE) 


