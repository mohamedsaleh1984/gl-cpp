# Compiler and flags
CXX = g++
CXXFLAGS = -std=c++11 -Wall -DGLEW_STATIC

# Include directories for GLFW and GLM
INCLUDES = -I/usr/include

# Libraries to link against
LIBS = -lglfw -lGL -lGLEW -lX11 -lpthread -lXrandr -lXi

# Source files
SRCS = main.cpp

# Output binary
TARGET = MyOpenGLProject

# Build the executable
all: $(TARGET)

$(TARGET): $(SRCS)
	$(CXX) $(CXXFLAGS) $(INCLUDES) -o $(TARGET) $(SRCS) $(LIBS)

# Clean up the build
clean:
	rm -f $(TARGET)
