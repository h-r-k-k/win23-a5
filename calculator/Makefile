objects = main.o addition.o subtraction.o multiplication.o division.o

calculator: $(objects)
	cc -o calculator $(objects)

$(objects): operations.h

clean:
	rm -f $(objects)

.PHONY: clean




