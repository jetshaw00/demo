OBJS = assign_npd.o crossFile.o 
TARGET = program
.PHONY: all clean

all: $(TARGET)

$(TARGET): $(OBJS)
	$(CC) -o $@ $^

clean:
	rm -f $(TARGET) $(OBJS)
