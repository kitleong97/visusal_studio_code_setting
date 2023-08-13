Reference: 
用 VSCode 寫 C/C++ 教學
https://hackmd.io/@liaojason2/vscodecppwindows

First step:
Visual Studio Code install:
C++ Intellisense
C/C++

Other Download:
*** MinGW - Minimalist GNU for Windows ***
https://sourceforge.net/projects/mingw/

After install mingw    ***original mingw install location, set as default
1)Basic setup: Select as Mark for Installation
mingw32-gcc-g++ (bin)

2)All Packages: Select as Mark for Installation
mingw32-gdb (bin)

3)Installation --> Apply Change
Select Apply

File Explorer -->This PC -->Properties
Advanced system setting-->Environment variables
System variables-->Path
Add C:\MinGW\bin    ***original mingw install location


Final step:
Download this:
https://github.com/liaojason2/vscode-cpp-for-windows
put this in c++/.vscode  ***c++ is the place u write c, c++ program

Ctrl+Shift+B         進行編譯

Ctrl+Shift+`         開啟終端機, ` is near u '1' on u keyboard

./???.exe+Enter      執行程式, ??? is u program name
