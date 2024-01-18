all: verbose compile

verbose:
	@echo "Compiling 'parser_engine.cpp' as 'parser'..."

compile:
	@g++ tinyxml.cpp tinyxmlparser.cpp tinyxmlerror.cpp tinystr.cpp parser_engine.cpp -o parser

run:
	./parser
