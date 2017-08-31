## Running your first program

I believe that, among the operating systems, Linux is most friendly
to programmers. Because of its shell. A shell allows you to
talk to your computer, to issue commands to it. In Linux,  
you can install GNU C++ and an editor (say, Atom) with a single command:

   sudo apt-get install g++ atom

Lots of automatization can be done without any programming in C++,
just by writing shell commands. The Windows shell was traditionally
extremely weak compared to Linux, although it becomes a bit better
in the more recent versions. OSX is better than Windows, as it has
a powerful shell, but still, installing software is more difficult
than issuing a single command.

Of course for people already familiar with Windows, but not with
Linux, Linux and shell are just another things to learn -- but if
you are learning programming, why not learn this too? :)
This section will assume Linux, if you are using another OS, you will have to
find out how to make the compiler work on your own. One note:
since it is not possible to run two operating systems at once,
it might be the easiest to run Linux from a CD, or a virtual
machine, rather than to install it on your computer.
 
Let's create a workspace first:

  mkdir course

Change the working directory to course:

  cd course
  
Put easy.cpp and hello.cpp in this directory. The manual way is to
run the editor (say, Atom), open the webpages containing the 
files in your browser, copy the contents, paste them into the editor,
and save the files. Alternatively, simply run the following command,
which will download the files from the course:

  sudo apt-get install wget
  wget ...
  wget ...

Now, run the C++ compiler:

  g++ hello.cpp -o hello

And run the program:

  ./hello
  
Look at hello.cpp, should be easy to understand. You can try to modify it and
see whether it works. (Do not look at
easy.cpp though -- this one translates simple things into bare C++,
and it is quite difficult itself.) Happy coding!

