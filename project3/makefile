CGFLAGS=-Wall
OBJ=main.o Sample.o ProstyTest.o

LeniwyKlasyfikator: $(OBJ)
	g++ $(CGFLAGS) $(OBJ) -o LeniwyKlasyfikator

Sample.o: Sample.cpp
	g++ -c $(CGFLAGS) Sample.cpp

ProstyTest.o: ProstyTest.cpp
	g++ -c $(CGFLAGS) ProstyTest.cpp

main.o: main.cpp Sample.o ProstyTest.o
	g++ -c $(CGFLAGS) main.cpp

clean:
	rm -f LeniwyKlasyfikator main.o Sample.o ProstyTest.o
