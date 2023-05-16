##
## EPITECH PROJECT, 2023
## Makefile
## File description:
## makefile
##

SRC	=	$(wildcard *.c) \
		$(wildcard builtin/*.c) \
		$(wildcard list/*.c) \
		$(wildcard tree/*.c) \
		$(wildcard builtin/history/*.c) \
		$(wildcard builtin/echo/*.c)	\
		$(wildcard builtin/variables/*.c) \
		$(wildcard builtin/alias/*.c)


OBJ	=	$(SRC:.c=.o)

NAME	=	42sh

CFLAGS	=	-I./../include -g3

BACK =		../

FLAGS = -W -Wall -Werror

all:		$(NAME)

$(NAME):	$(OBJ)
			gcc -o $(NAME) $(OBJ) -L./../lib/ -lmy $(FLAGS)
			mv $(NAME) $(BACK)$(NAME)

clean:
			rm -f $(OBJ)

fclean:		clean
			rm -f $(BACK)$(NAME)

re:			fclean all
