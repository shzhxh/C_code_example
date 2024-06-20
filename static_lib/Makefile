CC = gcc

all:
	$(CC) -c -o add.o add.c
	$(CC) -c -o sub.o sub.c
	ar cr libm.a add.o sub.o
	$(CC) -L./ -o main.out main.c -lm
clean:
	rm *.a *.o main.out
