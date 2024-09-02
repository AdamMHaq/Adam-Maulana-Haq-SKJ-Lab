all: addition.exe dump run

addition.exe: addition.cpp
	g++ -o addition.exe addition.cpp

dump: addition.exe
	objdump -d addition.exe > addition.txt

clean:
	rm -f addition.exe addition.txt

run: addition.exe
	./addition.exe
