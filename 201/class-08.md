# Layout

- Normal Flow

  1- position:static

- I have not specified a width

  property for the heading
  element, so you can see how it
  stretches the width of the entire
  browser window by default.
  The paragraphs are restricted
  to 450 pixels wide. This shows
  how the elements in normal flow
  start on a new line even if they
  do not take up the full width of
  the browser window.

  2- position:relative

- Relative positioning moves an
  element in relation to where it
  would have been in normal flow.
  For example, you can move it 10
  pixels lower than it would have
  been in normal flow or 20% to
  the right.
  You can indicate that an element
  should be relatively positioned
  using the position property
  with a value of relative.
  You then use the offset
  properties (top or bottom and
  left or right) to indicate how
  far to move the element from
  where it would.

  3- position:absolute

- When the position property
  is given a value of absolute,
  the box is taken out of normal
  flow and no longer affects the
  position of other elements on
  the page. (They act like it is not
  there.)
  The box offset properties (top
  or bottom and left or right)
  specify where the element
  should appear in relation to its
  containing element.

4- position:fixed

- Fixed positioning is a type
  of absolute positioning that
  requires the position property
  to have a value of fixed.
  It positions the element in
  relation to the browser window.
  Therefore, when a user scrolls
  down the page, it stays in the
  exact same place. It is a good
  idea to try this example in your
  browser to see the effect.

- z-index:

  - When you use relative, fixed, or
    absolute positioning, boxes can
    overlap. If boxes do overlap, the
    elements that appear later in the
    HTML code sit on top of those
    that are earlier in the page.
    If you want to control which
    element sits on top, you can use
    the z-index property. Its value
    is a number, and the higher the
    number the closer that element
    is to the front. For example, an
    element with a z-index of 10
    will appear over the top of one
    with a z-index of 5.

- float

  - The float property allows you
    to take an element in normal
    flow and place it as far to the
    left or right of the containing
    element as possible.
    Anything else that sits inside
    the containing element will
    flow around the element that is
    floated.

- Screen Sizes:

  - Different visitors to your site will have different sized screens that show
    different amounts of information, so your design needs to be able to
    work on a range of different sized screens.

- Screen Resolution:

  - Resolution refers to the number of dots a screen shows per inch. Some
    devices have a higher resolution than desktop computers and most
    operating systems allow users to adjust the resolution of their screens.

- Page Sizes:

  - Because screen sizes and display resolutions vary so much, web
    designers often try to create pages of around 960-1000 pixels wide
    (since most users will be able to see designs this wide on their screens).

- Layout Grids:

  - Composition in any visual art (such as design, painting, or photography)
    is the placement or arrangement of visual elements — how they are
    organized on a page. Many designers use a grid structure to help them
    position items on a page, and the same is true for web designers.

![layout grid](https://tutorialseye.com/wp-content/uploads/c4006d54efae95c71c05dc7b4a79c1d0.png)

- Multiple Style Sheets:

  - @import:

    - Some web page authors split

    up their CSS style rules into
    separate style sheets. For
    example, they might use one
    style sheet to control the layout
    and another to control fonts,
    colors and so on.
    Some authors take an even
    more modular approach
    to stylesheets, creating
    separate stylesheets to control
    typography, layout, forms,
    tables, even different styles for
    each sub-section of a site.

  - link:

    - On this page you can see the other technique for including
      multiple style sheets. Inside the
      < head> element is a separate
      < link> element for each style
      sheet.
      The contents of site.css are
      identical to styles.css on the
      left hand page, except the code
      does not contain @import rules.
      As with all style sheets, if two
      rules apply to the same element
      then rules that appear later in a
      document will take precedence
      over previous rules.
