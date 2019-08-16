cmd:
    nasm -f macho64 -o  1.o 1.asm
    ld  -macosx_version_min 10.14  -o hello -e _main 1.o -lSystem

1.asm   hello world 程序。
2.asm   输入一个字符串，然后打印输出。
