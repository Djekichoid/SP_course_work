all: hello

hello: main.o hello_world.o
	g++ main.o hello_world.o -o hello

main.o: main.cpp
	g++ -c main.cpp

hello_world.o: hello_world.cpp
	g++ -c hello_world.cpp

clean:
	rm -rf *.o hello