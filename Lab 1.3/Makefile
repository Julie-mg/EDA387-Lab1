OUT := ""

all: server client-simple client-multi

server: server-iterative.cpp
	g++ -Wall -Wextra -g3 server-iterative.cpp -o server
OUT += server

client-simple: client-simple.cpp
	g++ -Wall -Wextra -g3 client-simple.cpp -o client-simple
OUT += client-simple

client-multi: client-multi.cpp
	g++ -Wall -Wextra -g3 client-multi.cpp -o client-multi
OUT += client-multi

clean:
	rm -rf $(OUT) *.dSYM
