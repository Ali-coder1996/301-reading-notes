# Text

When creating a web page, you add tags
(known as markup) to the contents of the
page. These tags provide extra meaning
and allow browsers to show users the
appropriate structure for the page.
In this chapter we focus on how to add markup to the text that
appears on your pages. You will learn about:

- Structural markup: the elements that you can use to
  describe both headings and paragraphs
- Semantic markup: which provides extra information; such
  as where emphasis is placed in a sentence, that something
  you have written is a quotation (and who said it), the
  meaning of acronyms.

**1- Headings:**

**- HTML has six levels of headings:**

- is used for main headings
  h2 is used for subheadings
  If there are further sections
  under the subheadings then the
  h3 element is used, and so
  on Browsers display the contents of
  headings at different sizes.

- The contents of an h1 element is
  the largest, and the contents of
  an h6 element is the smallest.
  The exact size at which each
  browser shows the headings
  can vary slightly.

  - Users can also
    adjust the size of text in their
    browser. You will see how to
    control the size of text, its color,
    and the fonts used when we
    come to look at CSS.

**2- Paragraph :**

To create a paragraph, surround
the words that make up the
paragraph with an opening tag and closing tag.
By default, a browser will show
each paragraph on a new line
with some space between it and
any subsequent paragraphs.
![paragraph](https://www.web4college.com/html/Element.png)

**3- Bold & It alic:**

- By enclosing words in the tags
  b and /b we can make
  characters appear bold.
  The b element also represents
  a section of text that would be
  presented in a visually different
  way (for example key words in a
  paragraph) although the use of
  the b element does not imply
  any additional meaning.

- By enclosing words in the tags
  we can make
  characters appear italic.
  The i element also represents
  a section of text that would be
  said in a different way from
  surrounding content

- such as
  technical terms, names of ships,
  foreign words, thoughts, or other
  terms that would usually be
  italicized.

**4- Line Breaks & Horizontal Rules:**

- As you have already seen, the
  browser will automatically show
  each new paragraph or heading
  on a new line. But if you wanted
  to add a line break inside the
  middle of a paragraph you can
  use the line break tag br.

- To create a break between
  themes

- such as a change of
  topic in a book or a new scene
  in a play
- you can add a
  horizontal rule between sections
  using the hr tag.

**6- Quotations:**

- The blockquote element is
  used for longer quotes that take
  up an entire paragraph. Note
  how the p element is still
  used inside the blockquote
  element.
  Browsers tend to indent the
  contents of the blockquote
  element, however you should not
  use this element just to indent a
  piece of text

- rather you should
  achieve this effect using CSS.

## Introducing css

- Using External CSS:

  - The link element can be used
    in an HTML document to tell the
    browser where to find the CSS
    file used to style the page. It is an
    empty element (meaning it does
    not need a closing tag), and it
    lives inside the head element.
    It should use three attributes:
  - This specifies the path to the
    CSS file (which is often placed in
    a folder called css or styles).
  - This specifies the relationship
    between the HTML page and
    the file it is linked to. The value
    should be stylesheet when
    linking to a CSS file.

- Using Internal CSS:

  - You can also include CSS rules
    within an HTML page by placing
    them inside a style element,
    which usually sits inside the
    head element of the page.
    The style element should use
    the type attribute to indicate
    that the styles are specified in
    CSS. The value should be text/
    css.
  - When building a site with more
    than one page, you should use
    an external CSS style sheet. This:

  - Allows all pages to use the
    same style rules (rather than
    repeating them in each page).
  - Keeps the content separate
    from how the page looks.
  - Means you can change the
    styles used across all pages
    by altering just one file
    (rather than each individual
    page).

### basic javascript

- WHAT IS A VARIABLE?
  - A script will have to temporarily
    store the bits of information it
    needs to do its job. It can store this
    data in variables.
    When you write JavaScript, you have to tell the
    interpreter every individual step that you want it to
    perform. This sometimes involves more detail than
    you might expect.
    Think about calculating the area of a wall; in math
    the area of a rectangle is obtained by multiplying two
    numbers:
    **width x height = area**
- You may be able to do calcula tions like this in
  your head, bu t when writing a script to do this
  calculation, you need to give the computer very
  detailed instructions. You might tell it to perform the
  following four steps in order: 1. Remember the value for width 2. Remember the value for height 3. Multiply width by height to get the area 4. Return the result to the user
  In this case, you would use vari ables to "remember"
  the va lues for width and height. (This also illustrates
  how a scrip( contains very explicit instructions about
  exactly what you want the computer to do.)
  You can compare variables to short-term memory,
  because once you leave the page, the browser will
  forget any information it holds.

- DATA TYPES:

- NUMERIC DATA TYPE
  The numeric data type handles
  numbers.
  0.75
  For tasks that involve counting
  or calculating sums, you will
  use numbers 0-9. For example,
  five thousand, two hundred and
  seventy-two would be written
  5272 (note there is no comma
  between the thousands and
  the hundreds). You can also
  have negative numbers (such
  as -23678) and decimals (three
  quarters is written as 0.75).

- STRING DATA TYPE
  The strings data type consists of
  letters and other characters.
  Note how the string data type is
  enclosed within a pair of quotes.
  These can be single or double
  quotes, but the opening quote
  must match the closing quote.
  Strings can be used when
  working with any kind of text.
  They are frequently used to add
  new content into a page and they
  can contain HTML markup.
- BOOLEAN DATA TYPE
  Boolean data types can have one
  of two va lues: true or false.
  true
  It might seem a little abstract at
  first, but the Boolean data type is
  actually very helpful.
  You can think of it a little like a
  light switch - it is either on or off.
  As you will see in Chapter 4,
  Booleans are helpful when
  determining which part of a
  script should run.

**ARRAYS:**

An array is a special type of variable. It doesn't
just store one value; it stores a list of values.

```bash
var colors;
colors ['white', 'black', ' custom '];
var el document.getElementByld('col ors');
el . textContent = col ors[O];
```

#### Decisions and Loops

- USING COMPARISON OPERATORS:

At the most basic level, you can
evaluate two variables using a
comparison operator to return a
t rue or f al se value.
In this example, a user is taking a
test, and the script te lls the user
whether they have passed this
round of the test.

```bash
var pass = 50; II Pass mark
var score = 90; II Score
II Check if t he user has passed
var hasPas sed = score >= pass ;
II Wr ite the message i nto the page
var el = document .getEl ementByld(' answe r ');
e 1 . t extContent = 'Leve 1 passed: ' + has Passed;
```

- USING LOGICAL AND:

- In this example, a math test
  has tworounds.Foreach round
  there are two variables: one
  holds the user's score for that
  round; the other holds the pass
  mark for that round.

```bash
var scorel = 8; II Round 1 score
var score2 = 8; II Round 2 score
var passl 6; II Round 1 pass mark
var pass2 = 6; II Round 2 pass mark
II Check whether user passed both rounds , store result in variable
var passBoth = (scorel >= passl) && (score2 >= pass2);
II Create message
var msg = 'Both rounds passed: ' + passBoth;
II Write the message i nto the page
var el = document.getElementBy!d( ' answer') ;
el.textContent = msg;
```

- USING LOGICAL OR & LOGICAL NOT:
- Here is the same test but this
  time using the logical OR operator
  to find out if the user has passed
  at least one of the two rounds.
  If they pass just one round, they
  do not need to retake the test.

- USING IF STATEMENTS:
  In this example, the i f statement
  is checking if the value currently
  held in a variable called score is
  50 or more.

```bash
var score 75; II Score
var msg; II Message
if (score>= 50) { II If score is 50 or higher
msg = 'Congratulations!';
msg += ' Proceed to the next round . ' ;
var el = document.getElementByld('answer ' ) ;
el .textContent = msg;
```

- USING IF ELSE STATEMENTS:

1. one set if the condition
   evaluates to true.

2. another set if the condition is
   false

```bash
var pass = 50;
var score = 75;
var msg;
II Pass mark
II Current score
II Message
II Select message to write based on score
if (score >= pass) {
msg = 'Congratulations, you passed!';
} else {
msg = 'Have another go!';
var el = document .getElementByld('answer');
el .textContent = msg;
```
