all: lab3

lab3: calculator.o calculator_new.o
	g++ calculator.o calculator_new.o -o lab3

calculator.o: calculator.cpp
	g++ -c calculator.cpp

calculator_new.o: calculator_new.cpp
	g++ -c calculator_new.cpp

clean:
	rm -rf *0 lab3
