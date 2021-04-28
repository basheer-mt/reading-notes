# <span style="color:#93329e">**CSS Transforms, Transitions, and Animations**</span>


## <span style="color:#a34a28">**Transforms**</span>
> With CSS3 came new ways to position and alter elements. Now general layout techniques can be revisited with alternative ways to size, position, and change elements. All of these new techniques are made possible by the transform property.


&nbsp;

## <span style="color:#a34a28">**Transform Syntax**</span>

`div {`

    -webkit-transform: scale(1.5);

        -moz-transform: scale(1.5);

            -o-transform: scale(1.5);

                transform: scale(1.5);

`}`





&nbsp;

## <span style="color:#a34a28">**2D Transforms**</span>

> Elements may be distorted, or transformed, on both a two-dimensional plane or a three-dimensional plane. Two-dimensional transforms work on the x and y axes, known as horizontal and vertical axes. Three-dimensional transforms work on both the x and y axes, as well as the z axis.

### **2D Rotate**

#### *HTML*
 `<figure class="box-1">Box 1</figure>`

`<figure class="box-2">Box 2</figure>`

#### *CSS*
`.box-1 {
  transform: rotate(20deg);
}`

`.box-2 {
  transform: rotate(-55deg);
}`

> To see how it works, here's a [Demo](https://codepen.io/shayhowe/pen/AKDIp)


### **2D Scale**
#### *HTML*

`<figure class="box-1">Box 1</figure>`

`<figure class="box-2">Box 2</figure>`

              
#### *CSS*

`.box-1 {
  transform: scale(.75);
}`

`.box-2 {
  transform: scale(1.25);
}`

> To see how it works, here's a [Demo](https://codepen.io/shayhowe/pen/khtnm)

### **2D Translate**

#### *HTML*

`<figure class="box-1">Box 1</figure>`

`<figure class="box-2">Box 2</figure>`

`<figure class="box-3">Box 3</figure>`

              
#### *CSS*

`.box-1 {
  transform: translateX(-10px);
}`

`.box-2 {
  transform: translateY(25%);
}`

`.box-3 {
  transform: translate(-10px, 25%);
}`

> To see how it works, here's a [Demo](https://codepen.io/shayhowe/pen/LqHwt)


## **2D Skew**
#### *HTML*
`<figure class="box-1">Box 1</figure>`

`<figure class="box-2">Box 2</figure>`

`<figure class="box-3">Box 3</figure>`

              
#### *CSS*

`.box-1 {
  transform: skewX(5deg);
}`

`.box-2 {
  transform: skewY(-20deg);
}`

`.box-3 {
  transform: skew(5deg, -20deg);
}`


>To see how it works, here's a [Demo](https://codepen.io/shayhowe/pen/LqHwt)


## **Combining Transforms**
#### *HTML*
`<figure class="box-1">Box 1</figure>`

`<figure class="box-2">Box 2</figure>`

              
#### *CSS*
`.box-1 {
  transform: rotate(25deg) scale(.75);
}`

`.box-2 {
  transform: skew(10deg, 20deg) translateX(20px);
}`

> To see how it works, here's a [Demo](https://codepen.io/shayhowe/pen/gLwly)













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