CC = gcc
CFLAGS = -Wall -O2
OBJS = main.o input.o output.o debug.o
TARGET = tsl

$(TARGET): $(OBJS)
	$(CC) -o $(TARGET) $(OBJS)

%.o: %.c
	$(CC) $(CFLAGS) -c $< -o $@

clean:
	rm -f $(OBJS) $(TARGET)
