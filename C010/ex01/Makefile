NAME=ft_cat
SRCS=srcs/main.c srcs/ft_algo.c
OBJS=${SRCS:.c=.o}
CC=gcc
CFLAGS=-Wall -Wextra -Werror

.c.o:
	${CC} ${CFLAGS} -c $< -o ${<:.c=.o}

all: ${NAME}

${NAME}: ${OBJS}
	${CC} -o ${NAME} ${OBJS}
clean:
	rm -f ${OBJS}

fclean: clean
	rm -f ${NAME}