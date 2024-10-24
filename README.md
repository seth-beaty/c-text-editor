# Kilo Text Editor
This is a text editor written in C. It is mostly complete, however, there is some functionality yet to be implemented. This is based on the tutorial found [here](https://viewsourcecode.org/snaptoken/kilo/), which in turn can be found at [this Github repo](https://github.com/codecrafters-io/build-your-own-x). 

## Running the Editor

To run this program, you will need a C compiler. There are several online options [this being one of them](https://www.onlinegdb.com/online_c_compiler) that also allows you to enter command line arguments. Alternatively, you can download one in your IDE or one is included on Linux (easiest way to run). After downloading the repo, in a Linux terminal (can be [used inside Windows using WSL](https://learn.microsoft.com/en-us/windows/wsl/install)), navigate to the directory containing `kilo.c`. The program is self-contained within `kilo.c`, so that's the only file you need.

Assuming you have a C compiler installed, to run this program:
1. Type `./kilo filename` where `filename` is the name of the file you wish to edit - e.g. `./kilo kilo.c` produces the below result:

![image](https://github.com/user-attachments/assets/6e01c437-dcfd-40ad-9a05-6948a79fca75)

After executing the command, we see the file in the terminal:

![image](https://github.com/user-attachments/assets/feabac85-2898-41b5-ab12-9179e8d91d8e)

In the case where no `filename` is passed, the user will see this screen instead:

![image](https://github.com/user-attachments/assets/27b4ac60-1035-4e98-95e1-94e5eb20b8b8)

Feel free to contact me with any questions!

TODO:
- [ ] Implement Syntax Highlighting
- [ ] Implement Undo/Redo
