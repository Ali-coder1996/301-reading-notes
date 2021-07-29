# Links

- Writing Links
  - Links are created using the < a> element. Users can click on anything
    between the opening < a> tag and the closing </a> tag. You specify
    which page you want to link to using the href attribute.

![link tag](https://www.computerhope.com/jargon/h/html-tag.gif)

- Linking to Other Sites

  - Links are created using the < a>
    element which has an attribute
    called href. The value of the
    href attribute is the page that
    you want people to go to when
    they click on the link.
    Users can click on anything that
    appears between the opening
    < a> tag and the closing < /a>
    tag and will be taken to the page
    specified in the href attribute.
    When you link to a different
    website, the value of the href
    attribute will be the full web
    address for the site, which is
    known as an absolute URL.

```bash
<p>Movie Reviews:
<ul>
<li><a href="http://www.empireonline.com">
Empire</a></li>
<li><a href="http://www.metacritic.com">
Metacritic</a></li>
<li><a href="http://www.rottentomatoes.com">
Rotten Tomatoes</a></li>
<li><a href="http://www.variety.com">
Variety</a></li>
</ul>
</p>
```

## Layout

![bolck and inline element](https://ictacademy.com.ng/wp-content/uploads/2017/10/inline-block-and-positioning-in-css-4-638.jpg)

- **Controlling the Position of Elements**

  - Normal flow:
    Every block-level element
    appears on a new line, causing
    each item to appear lower down
    the page than the previous one.
    Even if you specify the width
    of the boxes and there is space
    for two elements to sit side-byside,
    they will not appear next
    to each other. This is the default
    behavior (unless you tell the
    browser to do something else).

  - Relative Positioning:
    This moves an element from the
    position it would be in normal
    flow, shifting it to the top, right,
    bottom, or left of where it
    would have been placed. This
    does not affect the position of
    surrounding elements; they stay
    in the position they would be in
    in normal flow.

  - Absolute positioning:
    This positions the element
    in relation to its containing
    element. It is taken out of
    normal flow, meaning that it
    does not affect the position
    of any surrounding elements
    (as they simply ignore the
    space it would have taken up).
    Absolutely positioned elements
    move as users scroll up and
    down the page.

  - Fixed Positioning:
    This is a form of absolute
    positioning that positions
    the element in relation to the
    browser window, as opposed
    to the containing element.
    Elements with fixed positioning
    do not affect the position of
    surrounding elements and they
    do not move when the user
    scrolls up or down the page.

  - Floating Elements:
    Floating an element allows
    you to take that element out
    of normal flow and position
    it to the far left or right of a
    containing box. The floated
    element becomes a block-level
    element around which other
    content can flow.

- **position:relative**

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
    where it would have been in
    normal flow.
    To move the box up or down,
    you can use either the top or
    bottom properties.
    To move the box horizontally,
    you can use either the left or
    right properties.
    The values of the box offset
    properties are usually given in
    pixels, percentages or ems.

- **position:absolute**

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
    In this example, the heading has
    been positioned at the top of the
    page and 500 pixels from its left
    edge. The width of the heading is
    set to be 250 pixels wide.
    The width property has
    also been applied to the < p>
    elements in this example
    to prevent the text from
    overlapping and becoming
    unreadable.

- **position:fixed**

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
    To control where the fixed
    position box appears in relation
    to the browser window, the box
    offset properties are used.
    In this example, the heading
    has been positioned to the top
    left hand corner of the browser
    window. When the user scrolls
    down the page, the paragraphs
    disappear behind the heading.

- **z-index**

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

- Floating Elements

  - The float property allows you
    to take an element in normal
    flow and place it as far to the
    left or right of the containing
    element as possible.
    Anything else that sits inside
    the containing element will
    flow around the element that is
    floated.
    When you use the float
    property, you should also use the
    width property to indicate how
    wide the floated element should
    be. If you do not, results can be
    inconsistent but the box is likely
    to take up the full width of the
    containing element (just like it
    would in normal flow).

### WHAT IS A FUNCTION

- Functions let you group a series of statements together to perform a
  specific task. If different parts of a script repeat the same task, you can
  reuse the function (rather than repeating the same set of st atements).

![function declaration](https://i.pinimg.com/originals/aa/95/eb/aa95eb390c01d14933fc98b977a8d6cb.jpg)
