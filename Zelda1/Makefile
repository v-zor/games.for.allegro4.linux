CXX=g++
CFLAGS=-O
LIBS=-L/usr/lib/86_64-linux-gnu
all: main

main:
	$(CXX) -c main.c

	$(CXX) -o main *.o $(LIBS) -lalleg

clean:
	rm -f *.o main
