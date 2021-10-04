# Lists

- Ordered Lists:
  - The ordered list is created with
    the ol element.
  - Each item in the list is placed
    between an opening tag
    and a closing tag. (The li
    stands for list item.)

```bash
<ol>
<li>Chop potatoes into quarters</li>
<li>Simmer in salted water for 15-20
minutes until tender</li>
<li>Heat milk, butter and nutmeg</li>
<li>Drain potatoes and mash</li>
<li>Mix in the milk mixture</li>
</ol>
```

- Unordered Lists:
  - The unordered list is created
    with the element.
  - Each item in the list is placed
    between an opening tag
    and a closing tag. (The li
    stands for list item.)

```bash
<ul>
<li>1kg King Edward potatoes</li>
<li>100ml milk</li>
<li>50g salted butter</li>
<li>Freshly grated nutmeg</li>
<li>Salt and pepper to taste</li>
</ul>
```

- Definition Lists
  - **dl:** The definition list is created with
    the element and usually
    consists of a series of terms and
    their definitions.
    Inside the element you will
    usually see pairs of and elements.
  - **dt:** This is used to contain the term
    being defined (the definition
    term).
  - **dd:** This is used to contain the
    definition.

```bash
<dl>
<dt>Sashimi</dt>
<dd>Sliced raw fish that is served with
condiments such as shredded daikon radish or
ginger root, wasabi and soy sauce</dd>
<dt>Scale</dt>
<dd>A device used to accurately measure the
weight of ingredients</dd>
<dd>A technique by which the scales are removed
from the skin of a fish</dd>
<dt>Scamorze</dt>
<dt>Scamorzo</dt>
<dd>An Italian cheese usually made from whole
cow's milk (although it was traditionally made
from buffalo milk)</dd>
</dl>
```

## Boxes

- Limiting Width:

  - Some page designs expand and
    shrink to fit the size of the user's
    screen. In such designs, the
    min-width property specifies
    the smallest size a box can be
    displayed at when the browser
    window is narrow, and the
    max-width property indicates
    the maximum width a box can
    stretch to when the browser
    window is wide.

- Limiting Height:

  - In the same way that you might
    want to limit the width of a box
    on a page, you may also want
    to limit the height of it. This is
    achieved using the min-height
    and max-height properties.
    The example on this page
    demonstrates these properties
    in action. It also shows you what
    happens when the content of the
    box takes up more space than
    the size specified for the box.

- Overflowing Content:
  - The overflow property tells the
    browser what to do if the content
    contained within a box is larger
    than the box itself. It can have
    one of two values: - **hidden**
    This property simply hides any
    extra content that does not fit in
    the box. - **scroll**
    This property adds a scrollbar to
    the box so that users can scroll
    to see the missing content.
    On the left, you can see two
    boxes whose contents expand
    beyond their set dimensions. The
    first example has the overflow
    property with a value of hidden.
    The second example has the
    overflow property with a value
    of scroll.

```bash
<h2>Fender Stratocaster</h2>
<p class="one">The Fender Stratocaster or "Strat"
is one of the most popular electric guitars of
all time, and its design has been copied by many
guitar makers. It was designed by Leo... </p>
<h2>Gibson Les Paul</h2>
<p class="two">The Gibson Les Paul is a solid body
electric guitar that was first sold in 1952.
The Les Paul was designed by Ted McCarty... </p>
```

- Border, Margin, padding:

![border](https://tutorialehtml.com/assets_tutorials/img/boxmodel.gif)

- Change Inline/Block:

  - **inline:**
    This causes a block-level
    element to act like an inline
    element.
  - **block:**
    This causes an inline element to
    act like a block-level element.
  - **inline-block:**
    This causes a block-level
    element to flow like an inline
    element, while retaining other
    features of a block-level element.

- Box Shadows: The box-shadow property
  allows you to add a drop shadow
  around a box. It works just like
  the text-shadow property that
  you met on page 288. It must
  use at least the first of these two
  values as well as a color:
  - Horizontal offset:
    Negative values position the
    shadow to the left of the box.
  - Vertical offset:
    Negative values position the
    shadow to the top of the box.
  - Blur distance:
    If omitted, the shadow is a solid
    line like a border.

### SWITCH STATEMENTS

![switch statment](https://hajsoftutorial.com/java/wp-content/uploads/2014/12/0-1-Copy351.png)

- JavaScript can convert data
  types behind the scenes to
  complete an operation. This is
  known as type coercion. For
  example, a string could be
  converted to a number 1 in the
  following expression:(' 1' > 0).
  As a result, the above expression
  would evaluate to true.
  JavaScript is said to use weak
  typing because the data type
  for a value can change. Some
  other languages require that you
  specify what data type
  each variable will be. They are
  said to use strong typing.
  Type coercion can lead to
  unexpected values in your
  code (and also cause errors).
