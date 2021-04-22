# <span style="color:#93329e">**JS Debugging**</span>


## <span style="color:#a34a28">**Error Handling & Debugging**</span>
> - THE CONSOLE & DEV TOOLS
> - COMMON PROBLEMS
> - HANDLING ERRORS


&nbsp;

## <span style="color:#a34a28">**ORDER OF EXECUTION**</span>

> - ### To find the source of an error, it helps to know how scripts are processed.

> - The order in which statements are executed can be complex; some tasks cannot complete until another statement or function has been run:



&nbsp;

## <span style="color:#a34a28">**EXECUTION CONTEXTS**</span>

> The JavaScript interpreter uses the concept of execution contexts. There is one global execution context; plus, each function creates a new new execution context. They correspond to variable scope.



&nbsp;

## <span style="color:#a34a28">**Code Debugging**</span>
> Programming code might contain syntax errors, or logical errors.

- Many of these errors are difficult to diagnose.

- Often, when programming code contains errors, nothing will happen. There are no error messages, and you will get no indications where to search for errors.

- Searching for (and fixing) errors in programming code is called code debugging.

&nbsp;

## <span style="color:#a34a28">**JavaScript Debuggers**</span>
> Debugging is not easy. But fortunately, all modern browsers have a built-in JavaScript debugger.

- Built-in debuggers can be turned on and off, forcing errors to be reported to the user.

- With a debugger, you can also set breakpoints (places where code execution can be stopped), and examine variables while the code is executing.

- Normally, otherwise follow the steps at the bottom of this page, you activate debugging in your browser with the F12 key, and select "Console" in the debugger menu.


&nbsp;

## <span style="color:#a34a28">**The console.log() Method**</span>
> If your browser supports debugging, you can use console.log() to display JavaScript values in the debugger window


&nbsp;

## <span style="color:#a34a28">**The Setting Breakpoints**</span>
> In the debugger window, you can set breakpoints in the JavaScript code.

- At each breakpoint, JavaScript will stop executing, and let you examine JavaScript values.

- After examining values, you can resume the execution of code (typically with a play button).



&nbsp;

## <span style="color:#a34a28">**The debugger Keyword**</span>
- The `debugger` keyword stops the execution of JavaScript, and calls (if available) the debugging function.

- This has the same function as setting a breakpoint in the debugger.

- If no debugging is available, the debugger statement has no effect.

- With the debugger turned on, this code will stop executing before it executes the third line.




&nbsp;

## <span style="color:#a34a28">**Major Browsers' Debugging Tools**</span>

> Normally, you activate debugging in your browser with F12, and select "Console" in the debugger menu.

- Otherwise follow these steps:

## Chrome
- Open the browser.
- From the menu, select "More tools".
- From tools, choose "Developer tools".
- Finally, select Console.

## Firefox
- Open the browser.
- From the menu, select "Web Developer".
- Finally, select "Web Console".

&nbsp;

&nbsp;

&nbsp;


# Summary

- If you understand execution contexts (which have two stages) and stacks, you are more likely to find the error in your code.
- Debugging is the process of finding errors. It involves a
process of deduction.
- The console helps narrow down the area in which the error is located, so you can try to find the exact error.
- JavaScript has 7 different types of errors. Each creates its own error object, which can tell you its line number and gives a description of the error.
- If you know that you may get an error, you can handle
it gracefully using the try, catch, finally statements. Use them to give your users helpful feedback.