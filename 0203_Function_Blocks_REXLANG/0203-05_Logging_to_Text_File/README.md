Logging to text file using the REXLANG function block 
=====================================================

This folder contains the source files demonstrating the use of the REXLANG 
user-programmable function block of REX.

The user algorithm collects date, time and simulated temperature and stores the 
information into a text file when triggered. The algorithm itself is located in 
the *logging_rexlang.c* file.

Feel free to modify the algorithm to fit your needs, you can use arbitrary 
format of the log file. 

The log file (rexlog.txt) is located in data folder (by default /rex/data on 
Linux machines). 

Read the
[complete description of the REXLANG function block](https://www.rexcontrols.com/media/2.50.5/doc/ENGLISH/MANUALS/BRef/REXLANG.html)
for more details. 

## Timing of the project ##

The algorithm runs each 500 milliseconds (0.5 s). See the EXEC function block,  
tick x ntick0 = 0.05 x 10 = 0.5 

## Prerequisities ##
- RexCore must be installed and running on the target device.

## Running the example ##
- The **exec.mdl* file is the project main file.
- Open it with *RexDraw*, compile and download it to the target device.
- Switch to online mode and watch the algorithm.
- Observe the resulting text file.

## Documentation ##

- **Press F1 for help** on the selected function block in the *RexDraw* program.
- [REXLANG function block documentation](https://www.rexcontrols.com/media/2.50.5/doc/ENGLISH/MANUALS/BRef/REXLANG.html)
- [Function blocks of REX](https://www.rexcontrols.com/media/2.50.5/doc/ENGLISH/MANUALS/BRef/BRef_ENG.html)
- [RexDraw User Guide](https://www.rexcontrols.com/media/2.50.5/doc/ENGLISH/MANUALS/RexDraw/RexDraw_ENG.html)
- [Complete documentation of REX](http://www.rexcontrols.com/documentation-and-support)

## Additional information ##

- See also the examples on integrating external devices for additional examples
using the REXLANG function block
- Visit the [REX Controls company webpage](http://www.rexcontrols.com) 
for more information about the example projects and developing advanced 
automation and control solutions using REX.

