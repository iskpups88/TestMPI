EXECS=Main
MPICC?=mpicc

all: ${EXECS}

Main: Main.c
	${MPICC} -o Main Main.c

clean:
	rm -f ${EXECS}
