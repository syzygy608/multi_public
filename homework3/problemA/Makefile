CC := mpicc
CFLAGS := -Wall -O2 -lm
TARGET := hw3a

all: $(TARGET)

$(TARGET): main.c
	$(CC) -o $@ $^ $(CFLAGS)

judge:
	chmod +x judge.sh
	bash judge.sh

clean:
	rm -f $(TARGET)
	rm -rf output
