# giflib 5.2.1 for MacOS Darwin w dynamic-dylibs
 giflib 5.2.1 (currently the latest) modified to build with dynamic dylibs instead of the .so format used on Linux. Tested to build on MacOS Ventura 13.2 using the native GCC, Apple Clang, and Intel Classic C++ (icc) compiler. Automatic lto applied (-flto) in makefile, define additional parameters in shell variables $CFLAGS and $LDFLAGS
