all: 
	g++ main.cpp -Os -O2 -std=c++14 -o main.elf -lpthread

plot:
	cat "test1.txt" | ./main.elf > output.txt 
	gnuplot plot.gp

clean:
	rm -f *.elf
