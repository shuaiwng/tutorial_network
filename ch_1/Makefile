CC=gcc
SRC=unix_list.c
OBJ=unix_list.o
EXE=unix_list

${EXE}: ${OBJ}
	${CC} ${OBJ} -o ${EXE}

${OBJ}: ${SRC}
	${CC} -Wall -c ${SRC}


clean:
	rm ${OBJ} ${EXE}