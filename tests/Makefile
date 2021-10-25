TARGETS := $(patsubst %.cpp,%,$(wildcard *.cpp))
CXXFLAGS += -std=c++17 -ggdb -I ../include -I ../examples

all: $(TARGETS)

%: %.cpp Makefile
	$(CXX) $(CXXFLAGS) -o $@ $<

clean:
	rm -f $(TARGETS)
