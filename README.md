# SimpleStaticLibrary_Linux
gcc -w -c ctest1.c ctest2.c
ar -cvq libctest.a ctest1.o ctest2.o
gcc -o foo prog.c libctest.a

[ar]
The GNU ar program creates, modifies, and extracts from archives. An archive is a single file holding a collection of other files in a structure that makes it possible to retrieve the original individual files (called members of the archive).
-c:do not warn if the library had to be created
-v:be verbose
-q:quick append files to the archive

[gcc]
GCC is a short of GNU Compiler Collection, a C compiler for Linux.
-c:compiles source files without linking
-o:writes the build output to an output file
