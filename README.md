# How to learn modern C++

**A guide to the adventurer**<br>
First to learn modern C++ you have to choose an operating system. The C++ is the same in all of them, but the settings and some libs used are different. In this guide I focus on the development in Linux, but the info can also be useful for other operating systems. <br>

* In this context we start by installing Ubuntu Linux, as a stand alone machine or as a virtual machine. <br>
  [Ubuntu](https://www.ubuntu.com/download/desktop) <br>

* Install the Build Essential Tools on Ubuntu, they have the GCC compiler. You can also install CLang that uses LLVM instead. <br> 

```shell
sudo apt-get update
sudo apt-get install build-essential
```

* Install CMake <br>

```shell
sudo apt-get install cmake
```

* Install an IDE (Integrated Development Environment) or a editor, I choose Visual Studio Code to develop but also like to have Sublime Text to open a file quickly. Both work on Linux, Windows and Mac, and both are fast. <br>
  [Visual Studio Code](https://code.visualstudio.com/) <br>
  [Sublime Text](https://www.sublimetext.com/) <br>

* In Visual Studio Code, install the following Plugins directly  in the IDE (Square button on the left): <br>
  [C/C++ ... syntax highlighting, code completion and debugging](https://code.visualstudio.com/docs/languages/cpp) <br>
  [CMakeTools ... to generate automatically the CMake files](https://marketplace.visualstudio.com/items?itemName=vector-of-bool.cmake-tools) <br>
  [CMake ... syntax highlighting and code completion for CMake files](https://marketplace.visualstudio.com/items?itemName=twxs.cmake) <br>
  [Code Spell Checker... comments and code](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker) <br>
  [Markdown All in One ... markdown syntax highlighting and preview](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one) <br>
  [Better Comments ... TODO list's in code comments and more](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments) <br>

* In youtube search and see some videos on how to use Visual Studio Code and explore the menus and buttons, including the shortcuts.

* Read the following links on how to use the plugins in VSCode. How to create an C++ project with CMake, how to do Builds, how to Run and to use the Debugger, all inside VSCode: <br>
  [Getting started with C++ in VS Code](https://www.youtube.com/watch?v=dSGW-DLMnUc) <br>
  [CMake Tutorial](https://cmake.org/cmake/help/latest/guide/tutorial/index.html)

* Read the following on how to use CTest, to Unit Test your programs. <br>
  [Testing With CMake and CTest](https://cmake.org/cmake/help/book/mastering-cmake/chapter/Testing%20With%20CMake%20and%20CTest.html)

* Study the following to learn about **C and CPP package managers**. Conan and Vcpkg. <br>
  [Vcpkg Vs Conan: Best Package Manager For C++](https://matgomes.com/vcpkg-vs-conan-for-cpp/) <br>
  [JFrog Conan Center](https://conan.io/center/) <br>
  [Conan documentation](https://docs.conan.io/en/latest/introduction.html) <br>    

* C++ linter - **cppcheck** <br>
  [cppcheck - A tool for static C or C++ code analysis](https://cppcheck.sourceforge.io/) <br>
  [Github cppcheck](https://github.com/danmar/cppcheck)

* C++ Weekly with Jason Turner - Youtube Channel <br>
  [C++ Weekly with Jason Turner](https://www.youtube.com/c/lefticus1/videos) 

* Study this video on C++ from Derek Banas on youtube that summarizes the main features of the programming language. <br>
  [C++ Tutorial 2021](https://www.youtube.com/watch?v=6y0bp-mnYU0)

* Read the following small book on C++ from the inventor of C++, Bjarne Stroustrup. This book is updated with the Standard C++ 17 and talks a little bit of what would be C++20. This book was published before C++20. It has to be the second edition. While reading the book do many experiments with code from the book and make variations to the code in Visual Studio Code. <br>
  [A Tour of C++ 2nd Edition by Bjarne Stroustrup](https://www.stroustrup.com/tour2.html) 

* Read the small book on GCC that is free on the net. <br>
  [An Introduction to GCC: For the GNU Compilers GCC and G++ by Brian J. Gough, Richard M. Stallman](https://www.linuxtopia.org/online_books/an_introduction_to_gcc/index.html)

* Four good books on general programming with C++. <br>
  **C++ Primer 5th Edition - C++11** <br>
  by Stanley Lippman, Josée Lajoie, Barbara Moo <br>
  [Programming: Principles and Practice Using C++ 2nd Edition by Bjarne Stroustrup, C++11 and C++14](https://www.stroustrup.com/programming.html) <br>
  **C++ Crash Course - A Fast-Paced Introduction - C++ 17** <br>
  by Josh Lospinoso <br>
  **Effective Modern C++: 42 Specific Ways to Improve Your Use of C++11 and C++14** <br>
  by Scott Meyers <br>

* Read the following about design patterns. <br>
  **Design Patterns: Elements of Reusable Object-Oriented Software** <br>
  by Erich Gamma , Richard Helm and others <br
  1994

* Read the following free ebook to learn about algorithms. <br>
  [Competitive Programmer's Handbook by Antti Laaksonen](https://github.com/pllk/cphb/)

* To really understand a programming language and the craft of programming, it's necessary to study large programs, how they are implemented, what where the options, what where the decisions, to study the program's architecture. If possible, the large program should be well documented and well made! The following free book and repository are an excellent example of the craft of programming of a large scale system with high performance. <br>
  "This book has deservedly won an Academy Award. I believe it should also be nominated for a Pulitzer Prize." -- Donald Knuth  <br>
  [Physically Based Rendering: From Theory to Implementation 3rd Edition by Matt Pharr, Wenzel Jakob, Greg Humphreys](http://www.pbr-book.org/) <br>
  [Github with the project code](https://github.com/mmp/pbrt-v3)

* Three good online references for the STL (Standard Template Library). <br>
  [Microsoft C++ Standard Library Reference](https://docs.microsoft.com/en-us/cpp/standard-library/cpp-standard-library-reference) <br>
  [C++ reference at cppreference.com](https://en.cppreference.com/w/cpp) <br>
  You can see it off line and alter it's CSS to make a dark mode in <br
  [https://en.cppreference.com/w/Cppreference:Archives](https://en.cppreference.com/w/Cppreference:Archives) <br>
  [105 STL Algorithms in Less Than an Hour - CppCon 2018: Jonathan Boccara](https://www.youtube.com/watch?v=2olsGf6JIkU) <br>

* A good book on C++ concurrency. <br>
  **C++ Concurrency in Action 2nd Edition** <br>
  by Anthony Williams

If you do all this steps you will have a good knowledge of C++ and can start doing large problems in C++. <br>


## Links
* [Simple, zero-dependency garbage collection for C - mkirchner/gc](https://github.com/mkirchner/gc)
* [A Compiler Writing Journey](https://github.com/DoctorWkt/acwj)


## Rust
* You may be also interested in my guide on Rust. <br>
  **How to learn modern Rust** <br>
  [https://github.com/joaocarvalhoopen/How_to_learn_modern_Rust](https://github.com/joaocarvalhoopen/How_to_learn_modern_Rust)


## All my other guides
* The links to all my guides are in: <br>
  **Guides on Linux - Programming - Embedded - Electronics - Aeronautics** <br>
  [https://github.com/joaocarvalhoopen/Guides_Linux-Programming-Electronics-Aeronautics](https://github.com/joaocarvalhoopen/Guides_Linux-Programming-Electronics-Aeronautics)


## Have fun! 

Best regards,<br>
João Nuno Carvalho