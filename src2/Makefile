CXXFLAGS = -O3 -m64

WARNINGS  = -Wall
WARNINGS += -Wextra
WARNINGS += -pedantic
WARNINGS += -Weffc++
WARNINGS += -std=c++17

all: compile asm_windows
	g++ main.o xorshift_func_windows.o -o xorshift.exe ${CXXFLAGS} ${WARNINGS}

compile:
	g++ -c main.cpp -o main.o ${CXXFLAGS} ${WARNINGS}

asm_windows:
	as xorshift_func_windows.S -o xorshift_func_windows.o --64
