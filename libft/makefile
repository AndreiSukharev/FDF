NAME = libft.a
FLAGS = -c -Wall -Wextra -Werror -Iinclude/
SRC = *.c

$(NAME):
	gcc $(FLAGS) $(SRC)
	ar rc $(NAME) *.o
	ranlib $(NAME)

all: $(NAME)

clean:
	/bin/rm -f *.o
fclean: clean
	/bin/rm -f $(NAME)
re: fclean all
