CC=gcc
CFLAGS=-Wall -Wextra -Werror

all: phantom

phantom: phantom.c phantom.h
	$(CC) $(CFLAGS) -o $@ phantom.c

clean:
	rm -f phantom

fclean: 
	rm -f phantom

re: fclean all

PHONY: all clean fclean re


