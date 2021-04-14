# <span style="color:#93329e">**HTML Images; CSS Color & Text**</span>


## <span style="color:#a34a28">**Images**</span>
> -  How to add images to pages
> -  Choosing the right format
> -  Optimizing images for the web


## Reasons you might consider to add an image to a web page:

1. Include a logo, 
2. Photograph
3. Illustration
4. diagram 
5. chart.


&nbsp;

## <span style="color:#a34a28">**Adding Images**</span>

## `<img>`

> To add an image into the page you need to use an `<img>` element. This is an empty element (which means there is no closing tag). 

> It must carry the following two attributes:

### `src`
> This tells the browser where it can find the image file. This will usually be a relative URL pointing to an image on your own site.

### `alt`
> This provides a text description of the image which describes the image if you cannot see it.


&nbsp;

## <span style="color:#a34a28">**Height & Width of Images**</span>

### `height`

> This specifies the height of the image in pixels.

### `width`
> This specifies the width of the image in pixels.

&nbsp;

## <span style="color:#a34a28">**Where to Place Images in Your Code**</span>

### three examples of image placement that produce different results:

1. before a paragraph
   > The paragraph starts on a new line after the image.
2. inside the start of a paragraph
   > The first row of text aligns with the bottom of the image.
3. In the middle of a paragraph
   > The image is placed between the words of the paragraph that it appears in.

&nbsp;

## <span style="color:#a34a28">**Old Code: Aligning Images Horizontally**</span>

### `align`
> The align attribute was commonly used to indicate how the other parts of a page should flow around an image.

&nbsp;

## <span style="color:#a34a28">**Three Rules for Creating Images**</span>
## 1
> Save images in the right format
## 2
> Save images at the right size
## 3
> Use the correct resolution

&nbsp; 

## Image Formats: JPEG
&nbsp;
![tiger jpeg](https://upload.wikimedia.org/wikipedia/commons/thumb/4/41/Siberischer_tiger_de_edit02.jpg/1200px-Siberischer_tiger_de_edit02.jpg)

&nbsp;

## Image Formats: GIF
&nbsp;
![Tiger GIF](https://media2.giphy.com/media/82kRFGXWMaNVCJZhhG/200w.webp?cid=ecf05e470i9gzavzmey0mzaoxxvh8l0ql0pxmmz53l2lwa8h&rid=200w.webp&ct=g)
&nbsp;


## Image Dimensions
> The images you use on your website should be saved at the same width and height that you want them to appear on the page.

&nbsp;
## Image Resolution
> Images created for the web should be saved at a resolution of 72 ppi. The higher the resolution of the image, the larger the size of the file.

&nbsp;

## <span style="color:#a34a28">**HTML 5: Figure and Figure Caption**</span>

## `<figure>`
> Images often come with captions. HTML5 has introduced a new `<figure>` element to contain images and their caption so that the two are associated.

`<figcaption>`
> The `<figcaption>` element has been added to HTML5 in order to allow web page authors to add a caption to an image.

&nbsp;

<hr />
<hr />
<hr />

&nbsp;

# <span style="color:#af05aa">**Color**</span>

> - How to specify colors
> - Color terminology and contrast
> - Background color

&nbsp;

## <span style="color:#a34a28">**Foreground Color**</span>
## <span style="color:#af05aa">*color*</span>

> The color property allows you to specify the color of text inside an element. 

> You can specify any color in CSS in one of three ways:
- ### rgb values
   > These express colors in terms of how much red, green and blue are used to make it up. For example: rgb(100,100,90)
- ### hex codes
   > These are six-digit codes that represent the amount of red, green and blue in a color, preceded by a pound or hash # sign. For example: #ee3e80
- ### color names
   > There are 147 predefined color names that are recognized by browsers. For example: DarkCyan



&nbsp;

## <span style="color:#a34a28">**Background Color**</span>

## <span style="color:#af05aa">*background-color*</span>
> CSS treats each HTML element as if it appears in a box, and the background-color property sets the color of the background for that box.

&nbsp;

## <span style="color:#a34a28">**CSS 3: Opacity**</span>

## <span style="color:#af05aa">*opacity, rgba*</span>
> CSS3 introduces the opacity property which allows you to specify the opacity of an element and any of its child elements. The value is a number between 0.0 and 1.0 (so a value of 0.5 is 50% opacity and 0.15 is 15% opacity).

## <span style="color:#a34a28">**Fixed Positioning**</span>
## <span style="color:#af05aa">*position:fixed*</span>
>Fixed positioning is a type of absolute positioning that requires the position property to have a value of fixed.


## <span style="color:#a34a28">**CSS 3: HSL & HSLA**</span>
## <span style="color:#af05aa">*hsl, hsla*</span>
> The hsl color property has been introduced in CSS3 as an alternative way to specify colors. The value of the property starts with the letters hsl, followed by individual values inside parentheses for:
## `hue`
> This is expressed as an angle (between 0 and 360 degrees).

## `saturation`
> This is expressed as a percentage. 
## `lightness`
> This is expressed as a percentage with 0% being white, 50% being normal, and 100% being black.


&nbsp;

<hr />
<hr />
<hr />

&nbsp;

# <span style="color:#af05aa">**Text**</span>
> - Size and typeface of text
> - Bold, italics, capitals, underlines
> - Spacing between lines, words, and letters

## <span style="color:#a34a28">**Techniques That Offer a Wider Choice of Typefaces**</span>

### There are several ways to use fonts
1. Font-family 
2. Font-face 
3. Service-based Font-Face

## <span style="color:#a34a28">**Specifying Typefaces**</span>
## <span style="color:#af05aa">*font-family*</span>
> The font-family property allows you to specify the typeface that should be used for any text inside the element(s) to which a CSS rule applies.

## <span style="color:#a34a28">**Size of Type**</span>
## <span style="color:#af05aa">*font-size*</span>
> The font-size property enables you to specify a size for the font. There are several ways to specify the size of a font. The most common are:

## `pixels` 
> Pixels are commonly used because they allow web designers very precise control over how much space their text takes up. The number of pixels is followed by the letters px.

## `percentages`
> The default size of text in browsers is 16px. So a size of 75% would be the equivalent of 12px, and 200% would be 32px.

## `ems`
> An em is equivalent to the width of a letter m.

&nbsp;

## <span style="color:#a34a28">**More Font Choice**</span>
## <span style="color:#af05aa">*@font-face*</span>
> @font-face allows you to use a font, even if it is not installed on the computer of the person browsing, by allowing you to specify a path to a copy of the font, which will be downloaded if it is not on the user's machine.

&nbsp;

## <span style="color:#a34a28">**Bold**</span>
## <span style="color:#af05aa">*font-weight*</span>

> The font-weight property allows you to create bold text. There are two values that this property commonly takes:

## `normal`
> This causes text to appear at a normal weight.

## `bold`
> This causes text to appear **bold**.

&nbsp;

## <span style="color:#a34a28">**Italic**</span>
## <span style="color:#af05aa">*font-style*</span>

> If you want to create italic text, you can use the font-style property. There are three values this property can take:

## `normal`
> This causes text to appear in a normal style (as opposed to italic or oblique).
## `italic`
> This causes text to appear *italic*.


&nbsp;

## <span style="color:#a34a28">**UpperCase & LowerCase**</span>
## <span style="color:#af05aa">*text-transform*</span>
> The text-transform property is used to change the case of text giving it one of the following values:

## `uppercase`
This causes the text to appear UPPERCASE.
## `lowercase`
This causes the text to appear lowercase.
## `capitalize`
> This Causes The First Letter Of Each Word To Appear Capitalized.

&nbsp;

## <span style="color:#a34a28">**Underline & Strike**</span>
## <span style="color:#af05aa">*text-decoration*</span>
> The text-decoration property allows you to specify the following values:
## `none`
> This removes any decoration
already applied to the text.
## `underline`
> This adds a line underneath the
text.
## `overline`
> This adds a line over the top of
the text.
## `line-through`
> This adds a line through words.
## `blink`
> This animates the text to make it
flash on and off (however this is
generally frowned upon, as it is
considered rather annoying).


&nbsp;

## <span style="color:#a34a28">**Alignment**</span>
## <span style="color:#af05aa">*text-align*</span>

> The text-align property allows
you to control the alignment of
text. The property can take one
of four values:

## `left`
> This indicates that the text
should be left-aligned.
## `right`
> This indicates that the text
should be right-aligned.
## `center`
> This allows you to center text.
## `justify`
> This indicates that every line in
a paragraph, except the last line,
should be set to take up the full
width of the containing box.



&nbsp;

## <span style="color:#a34a28">**Styling Links**</span>
## <span style="color:#af05aa">*:link, :visited*</span>
## `:link`
This allows you to set styles
for links that have not yet been
visited.
## `:visited`
This allows you to set styles for
links that have been clicked on.





## <span style="color:#a34a28">**Summary**</span>

### TEXT

&nbsp;

> - There are properties to control t XX he choice of font, size,
weight, style, and spacing.
> -  There is a limited choice of fonts that you can assume
most people will have installed.
> -  If you want to use a wider range of typefaces there are
several options, but you need to have the right license
to use them.
> -  You can control the space between lines of text,
individual letters, and words. Text can also be aligned
to the left, right, center, or justified. It can also be
indented.
> -  You can use pseudo-classes to change the style of an
element when a user hovers over or clicks on text, or
when they have visited a link.
