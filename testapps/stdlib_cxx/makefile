CXXFLAGS+=-g -Wall -O0

OBJ=test.o otherclass.o

all: test

test: $(OBJ)
	$(CXX) -o $@ $^


clean:
	rm -f test
	rm -f *.o

distclean:
	@(MAKE) clean
	chmod a-x *.cpp
	chmod a-x makefile
	#rm -f *~
	chmod a+x start_gede.sh

