.PHONY : all 51 clean
CFLAGS=-O2 -Wall -fPIC
all :
	gcc $(CFLAGS) --shared -o protobuf.so -I../.. -I/usr/local/include -L/usr/local/bin -L../../build pbc-lua.c -lpbc -llua52

51 :
	gcc $(CFLAGS) --shared -o protobuf.so -I../.. -I/usr/local/include/luajit-2.0/ -L/usr/local/bin -L../../build pbc-lua.c -lpbc -lluajit-5.1

clean :
	rm protobuf.dll
