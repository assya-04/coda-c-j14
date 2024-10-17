# Makefile

NAME = exo4

SRCS = exo4.c

all :  $(NAME)

$(NAME): $(SRCS)
	gcc $(SRCS) -o $(NAME) `sdl2-config --cflags --libs` -lSDL2_image

fclean:
	rm -f $(NAME)

re: fclean all
