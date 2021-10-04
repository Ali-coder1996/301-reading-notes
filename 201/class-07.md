# Tables

- Basic Table Structure

  - The < table> element is used
    to create a table. The contents
    of the table are written out row
    by row.

  - You indicate the start of each
    row using the opening < tr> tag.
    (The tr stands for table row.)
    It is followed by one or more
    < td> elements (one for each cell
    in that row).
    At the end of the row you use a
    closing </tr> tag.

  - Each cell of a table is
    represented using a < td>
    element. (The td stands for
    table data.)
    At the end of each cell you use a
    closing </td> tag.

- Table Headings

- The < th> element is used just
  like the < td> element but its
  purpose is to represent the
  heading for either a column or
  a row. (The th stands for table
  heading.)
  Even if a cell has no content,
  you should still use a < td> or
  < th> element to represent
  the presence of an empty cell
  otherwise the table will not
  render correctly. (The first cell
  in the first row of this example
  shows an empty cell.)

```bash
<table>
<tr>
<th></th>
<th scope="col">Saturday</th>
<th scope="col">Sunday</th>
</tr>
<tr>
<th scope="row">Tickets sold:</th>
<td>120</td>
<td>135</td>
</tr>
<tr>
<th scope="row">Total sales:</th>
<td>$600</td>
<td>$675</td>
</tr>
</table>
```

## CREATING MORE OBJECT LITERALS

- Here you can see another object.
  Again it is called hote 1, but this
  time the model represents a
  different hotel. For a moment,
  imagine that this is a different
  page of the same travel website.
  The Park hotel is larger. It has
  120 rooms and 77 of them are
  booked.

- The only things changing in the
  code are the va lues of the hotel
  object's properties:

  - The name of the hotel
  - How many rooms it has
  - How many rooms are booked

- CREATING OBJECTS USING CONSTRUCTOR SYNTAX

  - On the right, an empty object
    called hote 1 is created using the
    constructor function.
    Once it has been created, three
    properties and a method are
    then assigned to the object.
    ( If the object already had any
    of these properties, this would
    overwrite the values in those
    properties.)

- **WHAT ARE BUILT-IN OBJECTS?**

  - Browsers come with a set of built-in objects that represent things like the
    browser window and the current web page shown in that window. These
    built-in objects act like a toolkit for creating interactive web pages.

- THE BROWSEROBJECT MODEL:

  - The window object represents the current
    browser window or tab. It is the topmost object
    in the Browser Object Model, and it contains
    other objects that tell you about the browser.

- USING THE BROWSER OBJECT MODEL

  - Here, data about the browser is
    col lected from the window object
    and its children, stored in the msg
    variable, and shown in the page.
    The+= operator adds data onto
    the end of the msg variable.

  - Two of the window object's
    properties, innerWidth and
    innerHeight, show width and
    height of the browser window.

  - Child objects are stored as
    properties of t heir parent object.
    So dot notation is used to access
    them, just like you would access
    any other property of that object.

  - The element whose id
    attribute has a value of info is
    selected, and the message that
    has been built up to this point is
    written into the page.

- THE DOCUMENTOBJECT MODEL: THE DOCUMENT OBJECT

  - The topmost object in the Document Object Model (or DOM) is the
    document object. It represents the web page loaded into the current
    browser window or tab. You meet its child objects in Chapter5.

- GLOBAL OBJECTS: NUMBER OBJECT

  - Whenever you have a value that is a number,
    you can use the methods and properties of the
    Number object on it.

- GLOBAL OBJECTS: DATE OBJECT (AND TIME)

  - Once you have created a Date object, the following methods let you set and retrieve the time and date that it represents.

-
