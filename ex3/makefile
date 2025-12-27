CFLAG=-Wall -g

SRCS:= $(wildcard *.c)

PROGS:= $(SRCS:.c=)

all: clean $(PROGS)

%: %.c
	$(CC) $(CFLAGS) -o $@ $<

clean:
	rm -f $(PROGS)
