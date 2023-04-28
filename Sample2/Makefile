# This is a simple sample makefile to compile more than one C file,
# and all file are in same folder
#
#CC := gcc
#
#sample2.exe: sample2.c functions.c
#	${CC} $^ -o $@
#
#clean:
#	rm -f *.exe *~ 

# Generic makefile where the files name are not hardcoded

CC := gcc
SRCS := $(wildcard *.c)

sample2.exe: ${SRCS}
	${CC} $^ -o $@

clean:
	rm -f *.exe *~ 



