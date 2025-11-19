CC = gcc

all: fork fileprog simple

fork: Lab5_1.c
        $(CC) $(CFLAGS) Lab5_1.c -o fork
        ./fork
fileprog: file1.o file2.o
        $(CC) $(CFLAGS) file1.o file2.o -o fileprog
        ./fileprog

file1.o: file1.c
        $(CC) $(CFLAGS) -c file1.c

file2.o: file2.c
        $(CC) $(CFLAGS) -c file2.c

simple: Lab5_6.c
        $(CC) $(CFLAGS) Lab5_6.c -o simple
        ./simple
