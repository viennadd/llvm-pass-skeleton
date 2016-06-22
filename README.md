看了 [LLVM for Grad Students](http://adriansampson.net/blog/llvm.html) 介绍，基于这个 Skeleton 可以简单实现 Capture C 程序的控制流

# llvm-pass-skeleton

A completely useless LLVM pass.

Build:

    $ cd llvm-pass-skeleton
    $ mkdir build
    $ cd build
    $ cmake ..
    $ make
    $ cd ..

Run:

    $ clang -Xclang -load -Xclang build/skeleton/libSkeletonPass.* something.c


