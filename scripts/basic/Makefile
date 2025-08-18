# Makefile simples para Assembly ARM
FILE = hello
ASM = $(FILE).s
OBJ = $(FILE).o
EXE = $(FILE)

all: 
	as -o $(OBJ) $(ASM)
	ld -o $(EXE) $(OBJ)

clean:
	rm -f *.out *.o
