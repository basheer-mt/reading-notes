# <span style="color:#93329e">**HTML Tables; JS Constructor Functions**</span>

## <span style="color:#93329e">**Tables**</span>

> - How to create tables
> - What information suits tables
> - How to represent complex data in tables

&nbsp;

## <span style="color:#a34a28">**Basic Table St ructure**</span>

## `<table>`
   >The `<table>` element is used to create a table. The contents of the table are written out row by row.
## `<tr>`

> You indicate the start of each row using the opening `<tr>` tag. (The tr stands for table row.) It is followed by one or more `<td>` elements (one for each cell in that row). At the end of the row you use a closing `</tr>` tag.

## `<td>`
> Each cell of a table is represented using a `<td>` element. (The td stands for table data.) At the end of each cell you use a closing `</td>` tag.

&nbsp;

## <span style="color:#a34a28">**Table Headings**</span>

## `<th>`
> The `<th>` element is used just like the `<td>` element but its purpose is to represent the heading for either a column or row. (The th stands for table heading.)

> You can use the scope attribute on the `<th>` element to indicate whether it is a heading for a column or a row. It can take the values: row to indicate a heading for a `row` or `col` to indicate a heading for a column.

&nbsp;

&nbsp;


## <span style="color:#a34a28">**Spanning Columns**</span>

> Someti]mes you may need the entries in a table to stretch across more than one column.

> The `colspan` attribute can be used on a `<th>` or `<td>` element and indicates how many columns that cell should run across.

 > ex: `<td colspan="2">` `<td colspan="3">`

## HTML:

> `<table>`

> `<tr>`

> `<th></th>`

> `<th>9am</th>`

> `<th>10am</th>`

> `<th>11am</th>`

> `<th>12am</th>`

> `</tr>`

> `<tr>`

> `<th>Monday</th>`

> `<td colspan="2">Geography</td>`

> `<td>Math</td>`

> `<td>Art</td>`

> `</tr>`

> `<tr>`

> `<th>Tuesday</th>`

> `<td colspan="3">Gym</td>`

> `<td>Home Ec</td>`

> `</tr>`

> `</table>`

&nbsp;

## Results:

<table>
<tr>
<th></th>
<th>9am</th>
<th>10am</th>
<th>11am</th>
<th>12am</th>
</tr>
<tr>
<th>Monday</th>
<td colspan="2">Geography</td>
<td>Math</td>
<td>Art</td>
</tr>
<tr>
<th>Tuesday</th>
<td colspan="3">Gym</td>
<td>Home Ec</td>
</tr>
</table>

&nbsp;

## <span style="color:#a34a28">**Spanning Rows**</span>

> You may also need entries in a table to stretch down across more than one row. The rowspan attribute can be used on a `<th>` or `<td>` element to indicate how many rows a cell should span down the table.


&nbsp;

## <span style="color:#a34a28">**Long Tables**</span>

> There are three elements that
help distinguish between the
main content of the table and
the first and last rows (which can
contain different content).


&nbsp;

## `<thead>`

> The headings of the table should sit inside the `<thead>` element.

## `<tbody>`

> The body should sit inside the `<tbody>` element.

## `<tfoot>`
> The footer belongs inside the `<tfoot>` element.

&nbsp;

&nbsp;

## Summary
### TABLES
> - The `<table>` element is used to add tables to a web page.
> - A table is drawn out row by row. Each row is created with the `<tr>` element.
> - Inside each row there are a number of cells represented by the `<td>` element (or `<th>` if it is a header).
> - You can make cells of a table span more than one row or column using the rowspan and colspan attributes.
> - For long tables you can split the table into a `<thead>`, `<tbody>`, and `<tfoot>`.

&nbsp;

<hr>
<hr>
<hr>

&nbsp;

## <span style="color:#93329e">**Domain Modeling**</span>

> Domain modeling is the process of creating a conceptual model for a specific problem. And a domain model that's articulated well can verify and validate your understanding of that problem.

### Here's some tips to follow when building your own domain models.

1. ### When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.

2. ### Model its attributes with a constructor function that defines and initializes properties.

3. ### Model its behaviors with small methods that focus on doing one job well.

4. ### Create instances using the `new` keyword followed by a call to a constructor function.

5. ### Store the newly created object in a variable so you can access its properties and methods from **outside**.

6. ###  Use the `this` variable within methods so you can access the object's properties and methods from **inside**.

&nbsp;


## <span style="color:#a34a28">**Functions, Methods, & Objects**</span>

- ### Functions allow you to group a set of related statements together that represent a single task.

- ### Functions can take parameters (informatiorJ required to do their job) and may return a value.

- ### An object is a series of variables and functions that represent something from the world around you.

- ### In an object, variables are known as properties of the object; functions are known as methods of the object.

- ### Web browsers implement objects that represent both the browser window and the document loaded into the browser window.

- ### JavaScript also has several built-in objects such as String, Number, Math, and Date. Their properties and methods offer functionality that help you write scripts.

- ### Arrays and objects can be used to create complex data sets (and both can contain the other).

