![GitHub](https://img.shields.io/github/license/guilhermepo2/gueepo2D)
[![Language](https://img.shields.io/badge/language-C++-blue.svg)](https://isocpp.org/)
[![Standard](https://img.shields.io/badge/c%2B%2B-17-blue.svg)](https://en.wikipedia.org/wiki/C%2B%2B17)
![GitHub repo size](https://img.shields.io/github/repo-size/MattPiet/MemoryMonitor)

This is a C++ Memory Monitor. It functions by overloading the new and delete operators and also setting up a macro for them to print in the line and file where something was allocated. 
This will run in any and all C++ projects but only manages memory that is allocated to the heap. 

To use simply add the header file to your project then include it ONLY IN CPP FILES it will cause errors if you include it in a header file. 
Also the array portion of this is a little tricky but essentially  if you are at any point using a array new and delete call then you need to put in the monitor or it may cause crashing.

If you dont want to run into array issues simply comment out the array portion and enjoy this monitor through the simple non array new and delete format
