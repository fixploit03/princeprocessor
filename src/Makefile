##
## Makefile for pp (Linux 64-bit only)
##

CFLAGS = -W -Wall -std=c99 -O2 -s -DLINUX

CC = gcc

all: pp64.bin

pp64.bin: pp.c mpz_int128.h
	$(CC) $(CFLAGS) -o $@ pp.c

clean:
	rm -f pp64.bin
