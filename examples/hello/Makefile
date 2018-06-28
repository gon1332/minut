.POSIX:
CC     = gcc
CFLAGS = -std=c11 -Wall -I../../

all: hello

%: %.c
	$(CC) $(CFLAGS) -o $@.out $<

clean:
	rm -f *.out
