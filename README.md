# asm-practice
some assembly code, I do for fun
# Running `hello_x86_64.asm`
```sh
nasm -f elf64 -o hello.o hello_x86_64.asm && ld -s -o hello hello.o && ./hello
```
