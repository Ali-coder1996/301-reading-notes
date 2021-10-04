# Images

- Adding Images

  - To add an image into the page
    you need to use an < img >
    element. This is an empty
    element (which means there is
    no closing tag). It must carry the
    following two attributes:

- **src:**

This tells the browser where
it can find the image file. This
will usually be a relative URL
pointing to an image on your
own site. (Here you can see that
the images are in a child folder
called images — relative URLs
were covered on pages 83-84).

- **alt:**

This provides a text description
of the image which describes the
image if you cannot see it.

- Height & Widt of Images:

- **height:**

This specifies the height of the
image in pixels.

- **width:**
  This specifies the width of the
  image in pixels.
  Images often take longer to
  load than the HTML code that
  makes up the rest of the page.
  It is, therefore, a good idea to
  specify the size of the image
  so that the browser can render
  the rest of the text on the page
  while leaving the right amount of
  space for the image that is still
  loading.

```bash
<img src="images/quokka.jpg" alt="A family of
quokka" width="600" height="450" />
```

- Aligning Images Horizontally

- **The align** attribute was
  commonly used to indicate how
  the other parts of a page should
  flow around an image. It has
  been removed from HTML5
  and new websites should use
  CSS to control the alignment of
  images (as you will see on pages
  411-412).
  I have discussed it here because
  you are likely to come across
  it if you look at older code, and
  because some visual editors still
  insert this attribute when you
  indicate how an image should be
  aligned.
  The align attribute can take
  these horizontal values:

- **left:**

This aligns the image to the left
(allowing text to flow around its
right-hand side).

- **right:**

This aligns the image to the right
(allowing text to flow around its
left-hand side).

- Figure and Figure Caption

  - **< figure>**
    Images often come with
    captions. HTML5 has introduced
    a new < figure> element to
    contain images and their caption
    so that the two are associated.
    You can have more than one
    image inside the < figure>
    element as long as they all share
    the same caption.

  - **< figcaption>**
    The < figcaption> element has
    been added to HTML5 in order
    to allow web page authors to add
    a caption to an image.
    Before these elements were
    created there was no way to
    associate an < img> element with
    its caption.

## Color

- Foreground Color

  - **rgb values**
    These express colors in terms
    of how much red, green and
    blue are used to make it up. For
    example: rgb(100,100,90)

  - **hex codes**
    These are six-digit codes that
    represent the amount of red,
    green and blue in a color,
    preceded by a pound or hash #
    sign. For example: #ee3e80.

  - **color names**
    There are 147 predefined color
    names that are recognized
    by browsers. For example:
    DarkCyan
    We look at these three different
    ways of specifying colors on the
    next double-page spread.

- Background Color

  - CSS treats each HTML element
    as if it appears in a box, and the
    background-color property
    sets the color of the background
    for that box.
    You can specify your choice of
    background color in the same
    three ways you can specify
    foreground colors: RGB values,
    hex codes, and color names
    (covered on the next page).
    If you do not specify a
    background color, then the
    background is transparent.

- Opacity

  - CSS3 introduces the opacity
    property which allows you to
    specify the opacity of an element
    and any of its child elements.
    The value is a number between
    0.0 and 1.0 (so a value of 0.5
    is 50% opacity and 0.15 is 15%
    opacity).

![opacity](https://community.adobe.com/legacyfs/online/1775293_opecity.png)

### Text

![](https://www.w3schools.com/css/serif.gif)

- @font-face

  - allows you to use
    a font, even if it is not installed
    on the computer of the person
    browsing, by allowing you to
    specify a path to a copy of the
    font, which will be downloaded if
    it is not on the user's machine.
    Because this technique allows
    a version of the font to be
    downloaded to the user's
    computer, it is important that the
    license for the font permits it to
    be used in this way.
    You add the font to your style
    sheet using the @font-face
    rule, as shown on the right.

    ```bash
    @font-face {
    font-family: 'ChunkFiveRegular';
    src: url('fonts/chunkfive.eot');}
    h1, h2 {
    font-family: ChunkFiveRegular, Georgia, serif;}
    ```

- text-transform

  - **uppercase**
    This causes the text to appear
    uppercase.

  - **lowercase**
    This causes the text to appear
    lowercase.

  - **capitalize**
    This causes the first letter of
    each word to appear capitalized.
    In this example, the < h1>
    element is uppercase, the < h2>
    element is lowercase, and the
    credits are capitalized. In the
    HTML, the word by in the credits
    had a lowercase b.

    ```bash

    h1 {
    text-transform: uppercase;}
    h2 {
    text-transform: lowercase;}
    .credits {
    text-transform: capitalize;}
    ```

- text-indent

  - The text-indent property
    allows you to indent the first
    line of text within an element.
    The amount you want the line
    indented by can be specified in
    a number of ways but is usually
    given in pixels or ems.
