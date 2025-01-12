all: goo

goo: goo.o
	gcc -o goo goo.o

goo.o:
	nasm -f elf goo.asm
	