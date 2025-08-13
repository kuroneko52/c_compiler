CC = cc
CFLAGS = -std=c11 -g -static -Wall -Wextra -z noexecstack
LDFLAGS=-z noexecstack

9cc: 9cc.c

test: 9cc
		./test.sh

clean:
		rm -f 9cc *.o *~ tmp*

.PHONY: test clean
