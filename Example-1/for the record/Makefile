COMPILER = g++
EXECUTABLE = parser

all: verbose compile

verbose:
	@echo "Compiling 'parser_engine.cpp' as 'parser'..."

compile:
	@$(COMPILER) tinyxml.cpp tinyxmlparser.cpp tinyxmlerror.cpp tinystr.cpp parser_engine.cpp -o $(EXECUTABLE)

run:
	./$(COMPILER)
