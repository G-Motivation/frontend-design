.PHONY: clean
verilogCompiler = iverilog 
CFLAGS = -o

all: clean build test 
# iverilog -o alu alu.v 
# vvp alu

build: 
	$(verilogCompiler) ${CFLAGS} alu alu.v 

test: 
	vvp alu
clean:
	rm -rf alu
