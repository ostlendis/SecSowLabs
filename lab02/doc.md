# Lab 2
Before starting we set up the seedVM according to the instructions and uploaded the resource data to the VM.

## Step 1
use make to compile the c program 
Using make, we compiled the c program with gcc to the executable. 
We then run ```gdb ./retlib```. We set a breakpoint in the bof function with ```break bof``` and finally run the program with ```run```.
The breakpoint is reached at the bof() function and we can now run ```print system``` and ```print exit``` which will print information about the system() and exit() functions. The output is as follows:
```
$2 = {<text variable, no debug info>} 0xf7e12420 <system>
$3 = {<text variable, no debug info>} 0xf7e04f80 <exit>
```
as we can see the addresses of the system() and exit() functions are at 0xf7e12420 and 0xf7e04f80 respectively.

### what to document: 
- all the steps you take to exploit the vulnerability
- documentation of the solved tasks
- answer to the Security Questions