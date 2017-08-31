# Easy C++

## The purpose of this tutorial

This is meant to be an introduction to programming, especially programming in C++.
While C++ is commonly believed to be an extremely difficult language, I believe
that, when taught correctly, C++ is easier than C, Java,
or C#; some people find it [easier than Python](https://www.quora.com/Is-it-weird-that-I-find-C++-easier-than-Python).

However, usually, it is taught incorrectly. While C++ started as C plus Object
Oriented Programming, it has evolved a lot since then, especially in the
recent years (2011-).
However, teachers still teach C++ as they would teach C, or put too much
emphasis into complex things which can be avoided for simple programs,
such as pointers or object oriented programming.

They claim that C++ is a very complex language. While this is definitely
true, in many situations this is actually a good thing. First, contrary to
human languages, one does not need to learn it completely to use it. 
Second, the more complex the language is, the easier it is to describe
things in it.

Almost noone learns C++ in its entirety -- one does learn just a subset of this
language. Companies using C++ often have a listing of language features which
are allowed, and features which are banned, because it is better not to force
all the programmers in the company to be familiar with them.

A similar approach is used in this tutorial. It picks an *easy* subset of C++.
Some parts of the language are obsolete (backward compatibility with C or 
with older versions of C++) and no need to teach them. Some parts of the 
language are useful for experts, but cannot be appreciated by a beginner.
Some things can be done in multiple ways, the tutorial picks just one 
of them. However, this tutorial not only *removes* stuff -- it also *adds* some.
Programming can be seen as extending the 
programming language further and further: you create new functions which
extend the capabilities of the language, ultimately creating the function
which does the thing you need. This course is based on easy.cpp, which is a C++
file containing easy workarounds for some more complicated aspects of C++.
Extending the language is very important in programming practice -- there are
many libraries to use, and companies use their own.

This is a work in progress, and in a very early state. 
If you agree with the motivations above, 
contributions are welcome!

## Why learn to program, and why use C++ for that?

You could program a computer to:

* Solve puzzles. Computers are great in solving many kinds of puzzles,
and learning programming will allow you to use this. The algorithmic
programming contests are basically contests at solving puzzles, except
that you are allowed to use the computer, rather than doing everything
in your head. And as with other sports, they are fun even if you are
not the best in the world. The course will prepare you to start your
adventure with programming contests, or to solve puzzles and other
problems outside of the programming contest form.

* Create programs drawing pictures. This is what I have started with
myself: writing programs which draw nice pictures. 
Unfortunately, while on typical computers from 80's,
running a program drawing a line was a matter of simply writting
`LINE 10,10,200,200`, today's computers are complex enough that
this is no longer that simple, and generally becomes harder
and harder. This course contains libraries which should make
this somewhat easier again. Once you learn how to draw pictures,
you can go further: create games, animations, visualizations, graphs, and other fun stuff.
                                                           
* Generally learning programming is useful to test and improve your
skills in logical thinking.

* Learning programming is useful as a way to automate your tasks.
If you have ever done stupid, repetitive work on your computer, it
is possible that programming could have made the job easier.
However, C++ does not excel here -- it might be more appropriate
to learn shell or Python. (Learn these languages first might
be useful for other purposes; if you go the Linux route as suggested,
you will learn shell along the way.)

* Programming is fun! Of course it can be also used to earn money. But 
if your point is to earn money, this is probably not the best course.
Other courses, and other languages than C++, will allow you to make
money faster.

## What are other possible programming languages, and why not them?

* **C** is a subset of C++. Compared to C++, C is very old and
low level. The previous section should have made it clear why
learning another subset of C++ might be a better idea. 
I think every all-around computer scientist should have some
knowledge of low level programming, so I have no problem with
university courses of computer science teaching C. However,
for practical uses, higher level programming languages allow
you to express yourself without going too much into technical details
-- the compiler will fill them on its own, which is a good thing.

* I believe **Python** is actually quite a good language to start
programming. It is an interpreted language, one can type a command and 
have it immediately executed -- you instantly see the effects! It is
also widely used in practice, and has very nice syntax. It has many
great libraries, too. Many people like Python a lot, but there are 
also people who actually find C++ easier. 
I think it might be
actually a very good idea to read this section to know the disadvantages
of Python, learn its philosophy and advantages from another source,
and decide for yourself.

* C++ is statically typed and has
statically bound variables. This means that there is a big class of
bugs which will be caught by the static type checker, running which is
an integral part of the C++ programming process. 
In Python, the interpreter will not catch these bugs, so you
will actually have to run the program, test it, find that it does not
work in some situation, and look for the reason. This is necessary in
all languages
(functional programming languages are famous for having static
type checkers so good that even quite complex programs often work
correctly once the type checking is passed -- but still, this
is not infassible) but still, C++ makes this part easier.

* C++ is generally believed to be a very fast language. C++ programs
run fast. In many applications it is not very relevant, but it could
be important if you are interested in programming contests, games
programming, or when doing more complex calculations. Generally C#
and Java are fast enough for most uses, but Python is comparably
slow. Data scientists use Python quite successfully for their
complex computations, but making it run fast requires some
walkarounds, while C++ is fast naturally; and data scientists
using Python may need to
ultimately switch to a fast language such as C++ for performance.
C++
is in fact the most popular language used in programming contests.

* C++ is a multi-paradigm language. People say that C++ is based
on the object oriented programming (OOP) paradigm -- but this is an
outdated opinion to some extent. OOP was the first feature not in
C that was added to C++. I believe OOP is quite a complex concept,
and it is better to start learning programming without it. It is not
necessary in many areas of programming, including the ones which
are the focus of this course. (Though, it
is very useful in many areas where the money is.) Languages such as 
C# or Java are popular, but they focus too much on object
oriented programming in my opinion.

 