# <span style="color:#93329e">**The Duckett HTML book:**</span>

## In order to learn about creating web pages, this book is divided into three sections:

1. ## <span style="color:#e84545">**HTML**</span>
> - First chapter looking at how HTML is used to
create web pages.
3. ## <span style="color:#e84545">**CSS**</span>
> - This section starts with a chapter that explains how CSS uses rules to enable you to control the styling and layout of web pages.
4. ## <span style="color:#e84545">**Practical**</span>
> - End up with some helpful information that will assist you in building better websites.

____________________________________________________

![HTML CSS](https://elzero.org/wp-content/uploads/2019/06/practical-html-css.png)

____________________________________________________

# <span style="color:#35013f">**Structure**</span> 
## <span style="color:#28527a">**HTML Describes the Structure of Pages**</span>

#### This example explains how we see the web page and how the HTML code was written to display this.   
Note that the <span style="color:#0e49b5">**HTML**</span> code is in <span style="color:#0e49b5">**blue**</span>, and the <span style="color:#000000">**text**</span> you see on screen is in <span style="color:#000000">**black.**</span>

| <span style="color:#0e49b5">**HTML**</span> | <span style="color:#000000">**Text**</span> |
| - | - |
|  ![HTML CSS](./image/html_code.png) |  ![HTML CSS](./image/word.png) | 


### The HTML code (in blue) is made up of characters that live inside angled brackets — these are called HTML elements. 
> Elements are usually made up of two tags: an opening tag and a closing tag.
____________________________________________________
____________________________________________________
____________________________________________________

# A Closer Look at Tags

| <span style="color:#a34a28">**Opening Tag**</span> | <span style="color:#a34a28">**Closing Tag**</span> |
| - | - |
|  ![HTML CSS](./image/openning.png) |  ![HTML CSS](./image/closing.png) | 
____________________________________________________
____________________________________________________

# Body, Head & Title

# `<body>`

> Everything inside this element is shown inside the main browser window.

# `<head>`
> Before the `<body>` element you will often see a `<head>` element. This contains information about the page

# `<title>`
> The contents of the `<title>` element are either shown in the top of the browser, above where you usually type in the URL of the page you want to visit, or on the tab for that page.

| <span style="color:#0e49b5">**HTML**</span> | <span style="color:#000000">**RESULTS**</span> |
| - | - |
|  ![HTML CSS](./image/bht.png) |  ![HTML CSS](./image/results.png) | 

____________________________________________________

____________________________________________________


# <span style="color:#af05aa">**Extra Markup**</span>

>  - Specifying different versions of HTML
>  - Identifying and grouping elements
>  - Comments, meta information and iframes

## <span style="color:#a34a28">**The Evolution of HTML**</span>

> Since the web was first created, there have been several different versions of HTML.

1. HTML 4
    > Released 1997
2. XHTML 1.0
    > Released 2000    
3. HTML5
    > Re leased 2000    


## <span style="color:#a34a28">**DOCTYPES**</span>

>  Because there have been several versions of HTML, each web page should begin with a DOCTYPE declaration to tell a browser which version of HTML the page is using.

![Doctype](./image/doctype.png)

## <span style="color:#a34a28">**Comments in HTML**</span>
> `<!-- -->`

> If you want to add a comment to your code that will not be visible in the user's browser, you can add the text between these characters:

> `<!-- comment goes here -->`

## <span style="color:#a34a28">**ID Attribute**</span>
> Every HTML element can carry the id attribute. It is used to uniquely identify that element from other elements on the page.

> `<p id="pullquote">` This is a quote `</p>`

## <span style="color:#a34a28">**Class Attribute**</span>
> Every HTML element can also carry a class attribute. 
>The id and class attributes allow you to identify particular elements.

> `<p class="important">`Your Important paraghraph `</p>`

## <span style="color:#a34a28">**Grouping Text & Elements Inline**</span>
> The `<div>` and `<span>` elements allow you to group block-level and inline elements together.

## <span style="color:#a34a28">**IFrames**</span>
>  `<iframes>` cut windows into your web pages through which other pages can be displayed.

## <span style="color:#a34a28">**Information About Your Pages**</span>
> The `<meta>` tag allows you to supply all kinds of information about your web page.

## <span style="color:#a34a28">**Escape Characters**</span>
>  Escape characters are used to include special
characters in your pages such as <, >, and ©.

____________________________________________________
____________________________________________________
____________________________________________________


# <span style="color:#af05aa">**HTML5 Layout**</span>

> -  HTML5 layout elements
>  -  How old browsers understand new elements
>  -  Styling HTML5 layout elements with CSS

## <span style="color:#a34a28">**Headers & Footers `<header>` `<footer>`**</span>

> The `<header>` and `<footer>` elements can be used for:
> - The main header or footer that appears at the top or bottom of every page on the site.
> - A header or footer for an individual `<article>` or `<section>` within the page.

## <span style="color:#a34a28">**Navigation `<nav>`**</span>

> The `<nav>` element is used to contain the major navigational blocks on the site such as the primary site navigation.

## <span style="color:#a34a28">**Articles `<article>`**</span>

> The `<article>` element acts as a container for any section of a page that could stand alone and potentially be syndicated. 


## <span style="color:#a34a28">**Asides `<aside>`**</span>

> The `<aside>` element has two purposes, depending on whether it is inside an `<article>` element or not.
 > - When the `<aside>` element is used inside an `<article>` element, it should contain information that is related to the article but not essential to its overall meaning.
 > - When the `<aside>` element is used outside of an `<article>` element, it acts as a container for content that is related to the entire page.

 ## <span style="color:#a34a28">**Sections `<section>`**</span>
 
 > The `<section>` element groups related content together, and typically each section would have its own heading.

 ## <span style="color:#a34a28">**Heading Groups `<hgroup>`**</span>
 > The purpose of the `<hgroup>` element is to group together a set of one or more `<h1>` through `<h6>` elements so that they are treated as one single heading.

 ## <span style="color:#a34a28">**Sectioning El ements `<div>`**</span>
 > the `<div>` element will remain an important way to group together related elements, because you should not be using these new elements that you have just met for purposes other than those explicitly stated.


 ______________________________________________________________________________________________________
 ___________________________________________________

 # <span style="color:#af05aa">**Process & Design**</span>

 > - How to approach building a site.
 > - Understanding your audience and their needs
 >  - How to present information visitors want to see


## <span style="color:#a34a28">**HTML & CSS Process an Design**</span>

#### **Process that you can use when you are creating a new website.**

#### Things to consider when deciding to build a website:
>   1. Who is the Site For?  Target Audience:
        >- Individuals or companies?

> 2. Why People Visit YOUR Website:
   > - General or Specific goal? personl of proffessional?


> 3. What Your Visitors are Trying to Achieve?

> 4.  What Information Your Visitors Need:

> 5. How Of ten People Will Visit Your Site?

> 6. Site Map: the foundation of high quality SEO

![Site Map](https://cdn6.f-cdn.com/files/download/107256233/1.png)

> 7. WireFrames: simple sketch of the key information

![Wireframe](https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/ea9c8dbd-721d-4454-8951-481ad26b7bc5/contact-page-wireframe-mini.jpg)

> 8. Getting your message across using design:
   > - Content
   > - Prioritizing
   > - Organizing
   > - Visual Hierarchy
   > - grouping
   > - Similarity



   _________________________________________________
   _________________________________________________
   _________________________________________________


   
# <span style="color:#af05aa">**Programming with JavaScript**</span>

## <span style="color:#a34a28">**How Javascript Makes Web Pages More Interactive?**</span>
> 1.  Access Content
> 2.  Modify Content
> 3.  Program Rules
> 4.  React To Events

### Exaples:
 > - SlidesShows
 > - Forms

## <span style="color:#a34a28">**The ABC of Programming**</span>
> - Script and how to create one
> - How Computer fit in
> - How to write a script for a web page




### To write a script you need to first state your goal and then list the tasks that need to be completed in order to achieve it.

> `A Script is a series of instuctions that a computer can follow to achieve a goal.`

> 1.  Define the goal
> 2.  Design the script
> 3.  Code each step


