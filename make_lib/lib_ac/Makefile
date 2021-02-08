#sample Makefile
objects := $(patsubst %.c,%.o,$(wildcard *.c))
src     := $(wildcard *.c)

lib   : 
	gcc -c $(src)
	ar rcs libac.a $(objects)

main  :
	rm rm *.o
	gcc -o main lib_main.c -L. -lac
clean :
	rm *.o *.a  main
