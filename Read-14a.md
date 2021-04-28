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



