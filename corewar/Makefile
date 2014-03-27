##
## Makefile for Makefile in /home/rosey/rendu/CPE_2014_corewar
## 
## Made by rosey
## Login   <rosey@epitech.net>
## 
## Started on  Wed Mar 26 16:21:52 2014 rosey
## Last update Thu Mar 27 10:39:12 2014 rosey
##

NAME	= corewar

CC      = gcc

CFLAGS  += -W -Werror -Wextra -Wall
CFLAGS  += -ansi
CFLAGS  += -I.

LDFLAGS =

RM      = rm -f

SRCS    = main.c

OBJS    = $(SRCS:.c=.o)

all: $(NAME)

$(NAME): $(OBJS)
        $(CC) $(OBJS) -o $(NAME) $(LIB)

clean:
        $(RM) $(OBJS)

fclean: clean
        $(RM) $(NAME)

re: fclean all

.PHONY: all clean fclean re
