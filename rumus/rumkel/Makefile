CC=gcc
CFLAGS=-I.
DEPS = rumkeel.h
OBJ = pp.o rumkel.o 

%.o: %.c $(DEPS)
	$(CC) -c -o $@ $< $(CFLAGS)

rumkel: $(OBJ)
	$(CC) -o $@ $^ $(CFLAGS)
.PHONY: clean
