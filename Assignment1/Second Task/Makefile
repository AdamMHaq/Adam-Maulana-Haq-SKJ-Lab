all: multiplication.exe dump run

multiplication.exe: multiplication.cpp
	g++ -o multiplication.exe multiplication.cpp

dump: multiplication.exe
	objdump -d multiplication.exe > multiplication.txt

clean:
	rm -f multiplication.exe multiplication.txt

run: multiplication.exe
	./multiplication.exe
