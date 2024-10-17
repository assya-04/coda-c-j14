# Makefile

NAME = exo1

SRCS = exo1.c

all :  $(NAME)

$(NAME): $(SRCS)
	gcc $(SRCS) -o $(NAME) `sdl2-config --cflags --libs` -lSDL2_image

fclean:
	rm -f $(NAME)

re: fclean all
