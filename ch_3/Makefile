CC=gcc
SRC=tcp_serve_toupper.c
OBJ=tcp_serve_toupper.o
EXE=tcp_serve_toupper


${EXE}: ${OBJ}
	${CC} ${OBJ} -o ${EXE}

${OBJ}: ${SRC}
	${CC} -Wall -c ${SRC}


clean:
	rm ${OBJ} ${EXE}