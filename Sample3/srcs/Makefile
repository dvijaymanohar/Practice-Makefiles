# This is a simple sample makefile to compile more than one C file,
# and all file are in same folder

SRCS := $(wildcard *.c)
OBJS := $(SRCS:.c=.o)
HDRS := ../HDRS

CC := gcc
CFLAGS := -I. -I${HDRS}

sample3.exe: ${OBJS} 
	${CC} $^ -o $@ 

%.o: %.c
	${CC} -c $^ ${CFLAGS} 
	
sample3.o:functions.c ../HDRS/myheader.h

clean:
	rm -f *.exe *~ *.o


