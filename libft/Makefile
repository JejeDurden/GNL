# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: jdesmare <marvin@42.fr>                    +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2016/11/02 17:35:40 by jdesmare          #+#    #+#              #
#*   Updated: 2016/11/26 16:37:21 by jdesmare         ###   ########.fr       *#
#                                                                              #
# **************************************************************************** #

NAME = libft.a

CC = gcc $(FLAGS)

FLAG = -Wall -Wextra -Werror

SRC = ft_putchar.c			\
	  ft_putstr.c			\
	  ft_strlen.c			\
	  ft_strcmp.c			\
	  ft_strncmp.c			\
	  ft_isalpha.c			\
	  ft_isdigit.c			\
	  ft_isalnum.c			\
	  ft_isascii.c			\
	  ft_isprint.c			\
	  ft_tolower.c			\
	  ft_toupper.c			\
	  ft_strdup.c			\
	  ft_strcpy.c			\
	  ft_strncpy.c			\
	  ft_strcat.c			\
	  ft_strstr.c			\
	  ft_putnbr.c			\
	  ft_atoi.c				\
	  ft_strncat.c			\
	  ft_bzero.c			\
	  ft_memset.c			\
	  ft_memcpy.c			\
	  ft_memccpy.c			\
	  ft_memmove.c			\
	  ft_memchr.c			\
	  ft_memcmp.c			\
	  ft_strchr.c			\
	  ft_strrchr.c			\
	  ft_strnstr.c			\
	  ft_memalloc.c			\
	  ft_memdel.c			\
	  ft_strnew.c			\
	  ft_strdel.c			\
	  ft_strclr.c			\
	  ft_striter.c			\
	  ft_striteri.c			\
	  ft_strmap.c			\
	  ft_strmapi.c			\
	  ft_strequ.c			\
	  ft_strnequ.c			\
	  ft_strsub.c			\
	  ft_strjoin.c			\
	  ft_strtrim.c			\
	  ft_putendl.c			\
	  ft_putchar_fd.c		\
	  ft_putstr_fd.c		\
	  ft_putendl_fd.c		\
	  ft_putnbr_fd.c		\
	  ft_itoa.c				\
	  ft_strsplit.c			\
	  ft_strlcat.c			\
	  ft_lstnew.c			\
	  ft_lstdelone.c		\
	  ft_lstdel.c			\
	  ft_lstadd.c			\
	  ft_lstiter.c			\
	  ft_lstmap.c			\
	  ft_countwords.c		\
	  ft_power.c			\
	  ft_strupcase.c		\
	  ft_wordlen.c			\
	  ft_swap.c				\
	  ft_strrev.c			\
	  ft_sqrt.c				\

OBJ = $(SRC:.c=.o)

all: $(NAME)

$(NAME):
	@echo "Creating $(NAME) ..."
	@$(CC) -c $(SRC)
	@ar rc $(NAME) $(OBJ)
	@ranlib $(NAME)
	@echo "Done."

clean:
	@echo "Erasing .o files ..."
	@rm -f $(OBJ)
	@echo "Done."

fclean: clean
	@echo "Erasing $(NAME) ..."
	@rm -f $(NAME)
	@echo "Done."

re: fclean all clean
