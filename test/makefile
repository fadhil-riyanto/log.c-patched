logc:
	mkdir -p ../src/lib
	g++ ../src/log.cc -o ../src/lib/log.o -DLOG_USE_COLOR -c

test: logc
	g++ hello.cc ../src/lib/log.o -o hello