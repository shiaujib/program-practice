homework:Zip.o main.o
	g++ -o homework Zip.o main.o
main.o:main.cpp ZipCode.h Zip.cpp
	g++ -c main.cpp
Zip.o:Zip.cpp ZipCode.h main.cpp
	g++ -c Zip.cpp
