TARGET=gles31compute

all: Makefile $(TARGET)

$(TARGET): main.cpp
	g++ -ggdb -O0 -Wall -lEGL -lGLESv2 -lgbm  \
		-o $(TARGET) \
		main.cpp

clean:
	rm -f $(TARGET)
