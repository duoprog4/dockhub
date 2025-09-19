CC=gcc
CFLAGS=-c -Wall
OBJECTS=main.o isOdd.o

all: prog

prog: $(OBJECTS)
	$(CC) $(OBJECTS) -o prog

main.o: main.c
	$(CC) $(CFLAGS) main.c

%.o: %.cpp
	$(CC) $(CFLAGS) $<
clean:
	rm -rf *.o 
	rm -rf prog.exe