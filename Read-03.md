# <span style="color:#93329e">**HTML Lists, Control Flow with JS, and the CSS Box Model**</span>


## <span style="color:#a34a28">**Lists**</span>
> -  Numbered lists
> -  Bullet lists
> -  Definition lists

## HTML provides three different types: of lists:

1. Ordered Lists: 
   >are lists where each item in the list is numbered.

2. Unordered Lists: 
   >are lists that begin with a bullet point

3. Definition lists: 
   >are made up of a set of terms along with the definitions for each of those terms.

## <span style="color:#a34a28">**Ordered Lists**</span>

## `<ol>`

> The ordered list is created with
the `<ol>` element.

## `<li>`

> Each item in the list is placed
between an opening `<li>` tag
and a closing `</li>` tag.

## <span style="color:#a34a28">**Unordered Lists**</span>

`<ul>`

> The unordered list is created with the `<ul>` element.

`<li>`
> Each item in the list is placed between an opening `<li>` tag and a closing `</li>` tag.

## <span style="color:#a34a28">**Definition Lists**</span>

`<dl>`

> The definition list is created with the `<dl>` element and usually consists of a series of terms and their definitions.

`<dt>`
> This is used to contain the term being defined (the definition term).

`<dd>`
> This is used to contain the
definition.

## <span style="color:#a34a28">**Nested Lists**</span>
> You can put a second list inside an `<li>` element to create a sublist or nested list.

&nbsp;

<hr />
<hr />
<hr />

&nbsp;

# <span style="color:#af05aa">**Boxes**</span>

> - Controlling size of boxes
> -  Box model for borders, margin and padding
> -  Displaying and hiding boxes

## <span style="color:#a34a28">**Box Dimensions**</span>
## <span style="color:#af05aa">*width, height*</span>

> By default a box is sized just big enough to hold its contents. 

> To set your own dimensions for a box you can use the height and width properties.

### And there are Three ways to specify the size:
<dl>
<dt> Pixels </dt> 
<dd>Have been the most popular method because they allow designers to accurately control their size. </dd>
<dt>Percentages</dt>
<dd>The size of the box is relative to the size of the browser window or, if the box is encased within another box</dd>
<dt>ems</dt>
<dd>The size of the box is based on the size of text within it.</dd>

&nbsp;

> `Designers have recently started to use percentages and ems more for measurements as they try to create designs that are flexible across devices which have different-sized screens.`

&nbsp;

## <span style="color:#a34a28">**Limiting Width**</span>
## <span style="color:#af05aa">*min-width, max-width*</span>

&nbsp;

## <span style="color:#a34a28">**Limiting Height**</span>

## <span style="color:#af05aa">*min-hight, max-hight*</span>

&nbsp;

## <span style="color:#a34a28">**Overflowing Content**</span>

## <span style="color:#af05aa">*overflow*</span>


&nbsp;
<hr>
<hr>
<hr>

&nbsp;

# <span style="color:#af05aa">**Border, Margin & Padding**</span>
## <span style="color:#a34a28">**Border Width**</span>

## <span style="color:#af05aa">*border-width*</span>

&nbsp;


## <span style="color:#a34a28">**Border Style**</span>

## <span style="color:#af05aa">*border-style*</span>

&nbsp;


## <span style="color:#a34a28">**Border Color**</span>

## <span style="color:#af05aa">*border-color*</span>

&nbsp;

## <span style="color:#a34a28">**ShortHand**</span>

## <span style="color:#af05aa">*border*</span>

&nbsp;


## <span style="color:#a34a28">**Padding**</span>

## <span style="color:#af05aa">*padding*</span>

&nbsp;

## <span style="color:#a34a28">**Margin**</span>

## <span style="color:#af05aa">*margin*</span>

&nbsp;

&nbsp;

## <span style="color:#a34a28">**Centering Content**</span>


&nbsp;

## <span style="color:#a34a28">**Change Inline/Block**</span>

## <span style="color:#af05aa">*display*</span>

&nbsp;

## <span style="color:#a34a28">**Hiding Boxes**</span>

## <span style="color:#af05aa">*visibility*</span>


# Summary

## BOXES
- CSS treats each HTML e XX lement as if it has its own box.
- You can use CSS to control the dimensions of a box.
- You can also control the borders, margin and padding
for each box with CSS.
- It is possible to hide elements using the display and
visibility properties.
- Block-level boxes can be made into inline boxes, and
inline boxes made into block-level boxes.
- Legibility can be improved by controlling the width of
boxes containing text and the leading.
- CSS3 has introduced the ability to create image
borders and rounded borders.

&nbsp;
<hr>
<hr>
<hr>
&nbsp;

#  <span style="color:#93329e">***Programming with JavaScript***</span>

## <span style="color:#a34a28">**Decisions and Loops**</span>

## <span style="color:#a34a28">**Comparison Operators:**</span>

Evaluate a situation by comparing one value in the script to what you expect it might be. The result will be a Boolean: True or false.

- Is equal to **==** compares two values to check if they are the same

- Is not equal to **!=** compares two values to check if they are not the same

- Strict equal to **===** compares two values to verify that both the value and the data type are the same

- Strict not equal to **!==** compares two values to verify that both the value and the data type are different

- Greater than: 8 **>** 3 returns true

- Less than: 5 **<** 9 returns true

- Greater than or equal to **>=**

- Less than or equal to **<=**


_____________________________________________________________
## <span style="color:#a34a28">**Logical Operators**</span>
The operators used to return the result of multiple comparison operators

**((5 < 12) || (8 >= 2))**

- Logical AND **&&**

- Logical OR **||**

- Logical NOT **!**

______________________________________________________________

## <span style="color:#a34a28">**Loops**</span>
A loop is block of code that will keep running as long as the condition is true. The most common types of loops are:

- **For loop**; used when the code has to run specific number of times. It uses a counter as a condition

- **While loop**; used when the number of repetitions is unknown

- **Do while loop**; the fundamental difference between this loop and while loop is that the code will run at least once even if the condition evaluates to false

**  A for loop consists of variable initialization, condition, and update.


***Example***

Loop through the indices of an array to collect the car names from the cars array:


>var cars = ["BMW", "Volvo", "Saab", "Ford"];
v/ar text = "";
var i = 0;
while (i < cars.length) {
  text += cars[i] + "<br>";
  i++;
}   
