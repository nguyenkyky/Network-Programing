CC = gcc

server: server.o
	$(CC) server.o -o server

server.o: server.c
	$(CC) -c server.c

clean: 
	$(RM) server *.o *~ 