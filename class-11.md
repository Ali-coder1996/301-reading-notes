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

## Practical Information

- SEO is a huge topic and several books have been written on the subject.
  The following pages will help you understand the key concepts so you can
  improve your website's visibility on search engines.

- **The Basics**
  Search engine optimization (or
  SEO) is the practice of trying
  to help your site appear nearer
  the top of search engine results
  when people look for the topics
  that your website covers.

- **On-Page Techniques**
  On-page techniques are the
  methods you can use on your
  web pages to improve their
  rating in search engines.

- **Off-Page Techniques**
  Getting other sites to link to you
  is just as important as on-page
  techniques. Search engines help
  determine how to rank your
  site by looking at the number of
  other sites that link to yours.

- **On-Page seo**

  - In every page of your website there are seven key places where keywords
    (the words people might search on to find your site) can appear in order
    to improve its findability.

- **Analytics: Learning about your Visitors**

  - As soon as people start coming to your site, you can start analyzing
    how they found it, what they were looking at and at what point they are
    leaving. One of the best tools for doing this is a free service offered by
    Google called Google Analytics.

- **How Many People Are Coming to Your Site?**

  - The overview page gives you a snapshot of the key information you are
    likely to want to know. In particular, it tells you how many people are
    coming to your site.

- **What Are Your Visitors Looking At?**

  - The content link on the left-hand side allows
    you to learn more about what the visitors are
    looking at when they come to your site.

- **FT P & Third Party Tools**

  - To transfer your code and images from your
    computer to your hosting company, you use
    something known as File Transfer Protocol.

![FT P & Third Party Tools](https://i.pinimg.com/originals/28/f8/0a/28f80a164bf1ef890006ecc08ce0921f.png)
