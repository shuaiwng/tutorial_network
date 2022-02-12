CC=gcc
SRC=time_server.c
OBJ=time_server.o
EXE=time_server


${EXE}: ${OBJ}
	${CC} ${OBJ} -o ${EXE}

${OBJ}: ${SRC}
	${CC} -Wall -c ${SRC}


clean:
	rm ${OBJ} ${EXE}