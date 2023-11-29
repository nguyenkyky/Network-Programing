CC = gcc

main: client.o
	$(CC) client.o -o client

client.o: client.c
	$(CC) -c client.c

clean: 
	$(RM) client *.o *~ 