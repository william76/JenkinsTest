CXX=g++
CXX_OPTIONS=-std=c++14 -O3

all: build

build:
	${CXX} ${CXX_OPTIONS} helloworld.cxx -o helloworld.exe

clean:
	-rm helloworld.exe

test: build
	./helloworld.exe

