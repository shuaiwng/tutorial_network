CC=gcc
NAME = udp_serve_toupper
SRC=${NAME}.c
OBJ=${NAME}.o
EXE=${NAME}


${EXE}: ${OBJ}
	${CC} ${OBJ} -o ${EXE}

${OBJ}: ${SRC}
	${CC} -Wall -c ${SRC}


clean:
	rm ${OBJ} ${EXE}