SUMMARY

When you first download and extract the project, cd to the project directory 
and type the following at the terminal command line prompt:

    make
    ./runtests.sh
    
this will build the project and run all tests.

The output of runtests.sh for the intitial project distribution should be 
similar to (but not necessarily identical to) that shown in
README_test_r01_init.txt. 

Once you are working normally on the project you can just do:

    make 
    ./runtests.sh
    
when you want to re-build the project and run tests.

Or:

    make clean
    make
    ./runtests.sh
    
if making without cleaning temporary directories and binaries seems to 
cause unexpected errors.

Remember, "make" may give compilation errors. It is your job to fix them
if they are caused by code in files you have edited. If they are caused by 
code in other files, then report them using the programming support form
accessed from Canvas.

Compiler warnings may also be generated during compilation. Don't ignore 
warnings. They indicate problems with your code and you should fix them.

Marks can be deducted for ignoring compiler warnings

-----------------------------------------------------------------------------


