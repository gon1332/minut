.POSIX:
CC     = gcc
CFLAGS = -std=c11 -Wall -I../../

all: strings

%: %.c
	$(CC) $(CFLAGS) -o $@.out $<

clean:
	rm -f *.out
