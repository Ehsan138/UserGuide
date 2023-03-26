# Debugging Procedure

Because the debugging process can vastly vary depending on your needs, we can only provide a general guide on the typical debugging procedure.

Before you start, make sure that you have your project open.
## Steps:
1. Place a breakpoint on the line of code by clicking to the right of the line number.
    * If you need further explanation on breakpoints, read the Breakpoints section below.
2. Click on the Debug icon on the top right of the program.
3. Click on the arrow icon that suits your requirements.
4. To end the Debugger, click on the red square icon on the top right of the program.
5. Remove the breakpoint by clicking the red circle.

## Breakpoints
Breakpoints mark where you want to suspend the program execution so that you can examine the program at a deeper level. Breakpoints can be simple (for example, suspending the program on reaching some line of code) or involve more complex logic (checking against additional conditions, writing log messages, and so on).
Please note that breakpoints do not disappear upon termination of the Debugger. They must be removed explicitly (aside from temporary breakpoints).

PyCharm has two types of breakpoints: *line breakpoints* and *exception breakpoints*.

* Line breakpoints: suspends the program on reaching the line of code with the breakpoint. This type of breakpoints can be set on any executable line of code.
* Exception breakpoints: suspend the program when exceptions are thrown. 