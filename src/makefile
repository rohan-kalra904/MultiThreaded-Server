CC=clang
CFLAGS=-g
BINS=Server
OBJS=Server.o myQueue.o


all: $(BINS)

server: $(OBJS)
	$(CC) $(CFLAGS) -o $@ $^

%o: %.cpp
	$(CC) $(CFLAGS) -c -o $@ $^



clean:
	rm -rf *.dSYM $(BINS)