CC=gcc
SRC=tcp_client.c
OBJ=tcp_client.o
EXE=tcp_client


${EXE}: ${OBJ}
	${CC} ${OBJ} -o ${EXE}

${OBJ}: ${SRC}
	${CC} -Wall -c ${SRC}


clean:
	rm ${OBJ} ${EXE}