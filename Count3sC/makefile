# Makefile that contains the following two targets: 
# 1. Count3s - a native executable file that counts the number of 32 bit ints with the value 3s in the binary file threesData.bin
# 2. runCount3s - a target that launches the executable 
# There are three files required to build the executable file Count3s
# 1. countThrees.c
# 2. readInt32BitLE.h
# 3. eadInt32BitLE.c


OUT = Count3s
CC = gcc

CFILES := $(wildcard *.c)

$(OUT):
	$(CC) -o $(OUT) $(CFILES)

runCount3s:
	./$(OUT)

