all: main.o
	c++ -framework CoreFoundation main.o

run: all
	./a.out
	XDG_CONFIG_HOME=/xdg_config_home XDG_DATA_HOME=/xdg_data_home ./a.out

include ../Makefile.rules
