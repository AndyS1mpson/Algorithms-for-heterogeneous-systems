build/super-boring-task: main.cc linear-algebra.hh
	@mkdir -p build
	g++ -O3 -march=native -fopenmp main.cc -lOpenCL -o build/super-boring-task
build clang-builder:
	@mkdir -p build
	clang++ -std=c++11 -Xpreprocessor main.cc -framework OpenCL -o build/super-boring-task 
