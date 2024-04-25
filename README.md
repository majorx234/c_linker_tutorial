# c_linker_tutorial
- learn sth about compiler and linker tools

# 1st lesson (compile object files)
- compile to pobject files
  - `gcc -c main.c`
  - `gcc -c deepthought.c`
- take a look into symbols
  - `nm -sS main.o`
  - `nm -sS deepthought.o`
- compile to assembler:
  - `gcc -S main.c`
