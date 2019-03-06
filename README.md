# How to learn modern C++
**A guide to the adventurer**<br>
First to learn modern C++ you have to choose an operating system, the C++ is the same in all of them but the settings and the libs used are different. In this guide I focus on the development in Linux, but the info can also be useful for other operating systems. <br>

* In this context we start by installing Ubuntu Linux, as a stand alone machine or as a virtual machine. <br>
[Ubuntu](https://www.ubuntu.com/download/desktop) <br>

* Install the Build Essential Tools on Ubuntu, they have the GCC compiler. <br> 
sudo apt-get update <br>
sudo apt-get install build-essential

* Install CMake <br>
sudo apt-get install cmake<br>

* Install an IDE (Integrated Development Environment) and an editor, I choose Visual Studio Code to develop but also like to have Sublime Text to open a file quickly. Both work on Linux, Windows and Mac, and both are fast. <br>
[Visual Studio Code](https://code.visualstudio.com/) <br>
[Sublime Text](https://www.sublimetext.com/) <br>

* In Visual Studio Code, install the following Plugins directly  in the IDE (Square button on the left): <br>
[C/C++ ... syntax highlighting, code completion and debugging](https://code.visualstudio.com/docs/languages/cpp) <br>
[CMakeTools ... to generate automatically the CMake files](https://marketplace.visualstudio.com/items?itemName=vector-of-bool.cmake-tools) <br>
[CMake ... syntax highlighting and code completion for CMake files](https://marketplace.visualstudio.com/items?itemName=twxs.cmake) <br>
[Code Spell Checker... comments and code](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker) <br>
[Markdown All in One ... markdown syntax highlighting and preview](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one) <br>
[Better Comments ... TODO list's in code comments and more](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments) <br>

* In youtube search and see some videos on how to use Visual Studio Code and explore the menus and buttons.

* Read the following two links on how to create an C++ project with CMake, how to do Builds, how to Run and to use the Debugger: <br>
[Visual Studio Code C++ Quick Start](http://zompi.pl/visual-studio-code-c-quick-start/) <br>
[Quick start to CMake](http://zompi.pl/quick-start-to-cmake/)

* Read the following small book on C++ from the inventor of C++, Bjarne Stroustrup. This book is updated with the Standard C++ 17. It has to be the second edition. While reading the book do many experiments with code from the book and make variations to the code in Visual Studio Code. <br>
[A Tour of C++ 2nd Edition by Bjarne Stroustrup](https://www.amazon.com/Tour-2nd-Depth-Bjarne-Stroustrup/dp/0134997832/ref=sr_1_1?) 

* Read the small book on GCC that is free on the net. <br>
[An Introduction to GCC: For the GNU Compilers GCC and G++ by Brian J. Gough, Richard M. Stallman](https://www.linuxtopia.org/online_books/an_introduction_to_gcc/index.html)

* To really understand a programming language and the craft of programming, it's necessary to study large programs, how they are implemented, what where the options, what where the decisions, to study the program's architecture. If possible, the large program should be well documented and well made! The following free book and repository are an excellent example of the craft of programming of a large scale system with high performance. <br>
"This book has deservedly won an Academy Award. I believe it should also be nominated for a Pulitzer Prize." -- Donald Knuth  <br>
[Physically Based Rendering: From Theory to Implementation 3rd Edition by Matt Pharr, Wenzel Jakob, Greg Humphreys](http://www.pbr-book.org/) <br>
[Github with the project code](https://github.com/mmp/pbrt-v3)

If you do all this steps you will have a good knowledge of C++ and can start doing large problems in C++. <br>

Have fun! <br> 

Best regards,<br>
Joao Nuno Carvalho