#TestOS
*A toy operating system (if you can call it that)*

##Description
This is an operating system I wrote (or am going write) to plan around with core OS concepts. The first commit was built using the Meaty Skeleton Tutorial found [here](http://wiki.osdev.org/Meaty_Skeleton)

##Set Up

[follow this tutorial](http://wiki.osdev.org/GCC_Cross-Compiler) to set up the cross compiler on linux. Mac OSX users should probably [follow this tutorial](http://wiki.osdev.org/LLVM_Cross-Compiler)

I guess Mac OSX users should be able to use the first tutorial but GCC is not on Mac OSX. LLVM and Clang is aliased to GCC. The second tutorial claims that the llvm is easier to set up.

After that, modify the scripts to point to the right locations on your computer.

##Build
Just call `./clean.sh && ./headers.sh && ./iso.sh` to build an iso
