all:
	add_numbers

add_numbers:
	add_numbers.cpp
	g++ -o add_numbers.exe add_numbers.cpp

dump:
	add_numbers
	objdump -d add_numbers.exe > add_numbers.asm
clean:
	del -f add_numbers.exe add_numbers.asm
run:
	add_numbers
	add_numbers.exe