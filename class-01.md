# Introduction:

Before we look at the code used to build
websites it is important to consider the
different ways in which people access the web
and clarify some terminology.

- **Browsers:** People access websites using software called a web browser.
Popular examples include Firefox, Internet Explorer, Safari,
Chrome, and Opera.
In order to view a web page, users might type a web address into their browser, follow a link from another site, or use a
bookmark.

- **Web Servers:** When you ask your browser for
a web page, the request is sent
across the Internet to a special
computer known as a web
server which hosts the website.
Web servers are special
computers that are constantly
connected to the Internet, and
are optimized to send web pages
out to people who request them.

- **Devices:**People are accessing websites
on an increasing range of devices
including desktop computers,
laptops, tablets, and mobile
phones. It is important to
remember that various devices
have different screen sizes and
some have faster connections to
the web than others.

- **Screen readers:** *Screen readers* are programs
that read out the contents of a
computer screen to a user. They
are commonly used by people
with visual impairments.
In the same way that many
countries have legislations
that require public buildings
to be accessible to those with
disabilities, many laws have
also been passed that require
websites be accessible to those
with disabilities.



**All websites use HTML and CSS, but content
management systems, blogging software, and
e-commerce platforms often add a few more
technologies into the mix.**

>When you are looking at a
website, it is most likely that
your browser will be receiving
HTML and CSS from the web
server that hosts the site. The
web browser interprets the
HTML and CSS code to create
the page that you see.
Most web pages also include
extra content such as images,
audio, video, or animations and
this book will teach you how to
prepare them for use on the web
and then how to insert them into
your web pages.
Some sites also send JavaScript
or Flash to your browser, and you
will see how to add JavaScript
and Flash in your web pages.
Both of these technologies are
advanced topics that you can go
on to learn more about once you
have mastered HTML and CSS, if
you want to.



## How the Web Works:
When you visit a website, the web server
hosting that site could be anywhere in the
world. In order for you to find the location of
the web server, your browser will first connect
to a Domain Name System (DNS) server.


### Structure:

>HTM L Describes
the Structure
of Pages:

In the browser window you can see a web page that features exactly
the same content as the Word document you met on the page 18. To
describe the structure of a web page, we add code to the words we want
to appear on the page.
You can see the HTML code for this page below. Don't worry about what
the code means yet. We start to look at it in more detail on the next
page. Note that the HTML code is in blue, and the text you see on screen
is in black.

```
<html>
<body>
<h1>This is the Main Heading</h1>
<p>This text might be an introduction to the rest of the page. And if the page is a long one it might be split up into several sub-headings.<p>
<h2>This is a Sub-Heading</h2>
<p>Many long articles have sub-headings so to help you follow the structure of what is being written. There may even be sub-sub-headings (or lower-level headings).</p>
<h2>Another Sub-Heading</h2>
<p>Here you can see another sub-heading.</p>
</body>
</html>
```

The HTML code (in blue) is made up of characters that live inside angled
brackets — these are called HTML elements. Elements are usually
made up of two tags: an opening tag and a closing tag. (The closing tag
has an extra forward slash in it.) Each HTML element tells the browser
something about the information that sits between its opening and
closing tags.

>Attributes Tell Us
More About El ements:

Attributes provide additional information
about the contents of an element. They appear
on the opening tag of the element and are
made up of two parts: a name and a value,
separated by an equals sign.
```
<p lang="en-us">Paragraph in English</p>
```

- The attribute name indicates
what kind of extra information
you are supplying about the
element's content. It should be
written in lowercase.

- The value is the information
or setting for the attribute. It
should be placed in double
quotes. Different attributes can
have different values.

- Here an attribute called lang is
used to indicate the language
used in this element. The value
of this attribute on this page
specifies it is in US English.

```
<body>
You met the <body> element in the first example we created.
Everything inside this element is shown inside the main browser
window.

<head>
Before the <body> element you will often see a <head> element.
This contains information about the page (rather than information that is shown within the main part of the browser window that is highlighted in blue on the opposite page). You will usually find a 
element.

<title>
element inside the <head> <title> The contents of the <title> element are either shown in the top of the browser, above where
you usually type in the URL of the page you want to visit, or
on the tab for that page (if your browser uses tabs to allow you
to view multiple pages at the same time).
```

### Extra Markup :

**DOCTYPEs:**

- Because there have been
several versions of HTML, each
web page should begin with a
DOCTYPE declaration to tell a
browser which version of HTML
the page is using (although
browsers usually display the
page even if it is not included).
We will therefore be including
one in each example for the rest
of the book.
As you will see when we come to
look at CSS and its box model on
page 316, the use of a DOCTYPE
can also help the browser to
render a page correctly.
Because XHTML was written
in XML, you will sometimes
see pages that use the XHTML
strict DOCTYPE start with
the optional XML declaration.
Where this is used, it should be
the first thing in a document.
There must be nothing before it,
not even a space.



- Class attribute :
Every HTML element can
also carry a class attribute.
Sometimes, rather than uniquely
identifying one element within
a document, you will want a
way to identify several elements
as being different from the
other elements on the page.
For example, you might have
some paragraphs of text that
contain information that is more
important than others and want
to distinguish these elements, or
you might want to differentiate
between links that point to other
pages on your own site and links
that point to external sites.
To do this you can use the
class attribute. Its value
should describe the class it
belongs to. In the example on
the left, key paragraphs have a
class attribute whose value is
important.
The class attribute on any
element can share the same
value. So, in this example, the
value of important could be
used on headings and links, too.


>By default, using these attributes
does not affect the presentation
of an element. It will only change
their appearance if there is a CSS
rule that indicates it should be
displayed differently.

>In this example, CSS has been
applied to make elements with
a class attribute whose value
is important uppercase, and
elements with a class attribute
whose value is admittance red.

>If you would like to indicate that
an element belongs to several
classes, you can separate class
names with a space, as you can
see in the third paragraph in the
example above.




- Block element :
Some elements will always
appear to start on a new line in
the browser window. These are
known as block level elements.


**Examples of block elements are <h1>, <p>, <ul>, and <li>.**

- Inline element :

Some elements will always
appear to continue on the
same line as their neighbouring
elements. These are known as
inline elements.

**Examples of inline elements are <a>, <b>, <em>, and <img>.**

### HTML5 Layout:


>>For a long time, web page authors used <div> elements to group
together related elements on the page (such as the elements that form a
header, an article, footer or sidebar). Authors used class or id attributes
to indicate the role of the <div> element in the structure of the page.



>>HTML5 introduces a new set of elements that allow you to divide up the
parts of a page. The names of these elements indicate the kind of content
you will find in them. They are still subject to change, but that has not
stopped many web page authors using them already.



**Headers & Footers**

- The and elements can be used for:

- The main header or footer
that appears at the top or
bottom of every page on the
site.

- A header or footer for an
individual  within the page.
In this example, the 
element used to contain the site
name and the main navigation.
The  element contains
copyright information, along
with links to the privacy policy
and terms and conditions.
Each individual  and
 element can also
have its own  and
 elements to hold the
header or footer information for
that section within the page.

For example, on a page with several blog posts, each individual post can be thought of as a separate section. The  element can therefore be used to contain the title and date of each individual post, and the might contain links to share the article on social networking sites. Please note that all of the code shown in this chapter is referenced in one HTML
document which is called:
html5-layout.html


**Headers**
```
<header>
<h1>Yoko's Kitchen</h1>
<nav>
<ul>
<li><a href="" class="current">home</a></li>
<li><a href="">classes</a></li>
<li><a href="">catering</a></li>
<li><a href="">about</a></li>
<li><a href="">contact</a></li>
</ul>
</nav>
</header>
```

**Footers**
```
<footer>
&copy; 2011 Yoko's Kitchen
</footer>
```

**Navigation:**
```
<nav>
<ul>
<li><a href="" class="current">home</a></li>
<li><a href="">classes</a></li>
<li><a href="">catering</a></li>
<li><a href="">about</a></li>
<li><a href="">contact</a></li>
</ul>
</nav>
```

The nav element is used to
contain the major navigational
blocks on the site such as the
primary site navigation.
Going back to our blog example,
if you wanted to finish an article
with links to related blog posts,
these would not be counted as
major navigational blocks and
therefore should not sit inside a
nav element.
At the time of writing, some of
the developers that were already
using HTML5 decided to use the
nav element for the links that
appear at the bottom of every
page (links to things like privacy
policy, terms and conditions
and accessibility information).
Whether this will be widely
adopted is still yet to be seen.




**Figures:**

```
<figure>
<img src="images/bok-choi.jpg" alt="Bok Choi" />
<figcaption>Bok Choi</figcaption>
</figure>
```

You already met the figure
element in Chapter 5 when we
looked at images. It can be used
to contain any content that is
referenced from the main flow of
an article (not just images).
It is important to note that the
article should still make sense
if the content of the figure
element were moved (to another
part of the page, or even to a
different page altogether).
For this reason, it should only be
used when the content simply
references the element (and not
for something that is absolutely
integral to the flow of a page).

**Examples of usage include:**

- Images
- Videos
- Graphs
- Diagrams
- Code samples
- Text that supports the main
- body of an article


>The figure element should
also contain a figcaption
element which provides a text
decription for the content of
the figure element. In
this example, you can see a figure has been added inside
the article element.

**Sectioning El ements**

**Div:**

It may seem strange to follow
these new elements by revisiting
the div element again. (After
all, the new elements are often
going to be used in its place.)
However, the div element
will remain an important way to
group together related elements,
because you should not be using
these new elements that you
have just met for purposes other
than those explicitly stated.
Where there is no suitable
element to group a set of
elements, the div element will
still be used. In this example, it is
used as a wrapper for the entire
page.


### Process & Design:

- WireFrames:

  - A wireframe is a simple sketch of the key
information that needs to go on each page of a
site. It shows the hierarchy of the information
and how much space it might require.

- Designing Navigation :
  - Concise:Ideally, the navigation should
be quick and easy to read. It is
a good idea to try to limit the
number of options in a menu to
no more than eight links. These
can link to section homepages
which in turn link to other pages.
  - Clear:Users should be able to predict
the kind of information that
they will find on the page
before clicking on the link.
Where possible, choose single
descriptive words for each link
rather than phrases.

  - Selective:The primary navigation should
only reflect the sections or
content of the site. Functions
like logins and search, and legal
information like terms and
conditions and so on are best
placed elsewhere on the page.

  - Context:Good navigation provides
context. It lets the user know
where they are in the website at
that moment. Using a different
color or some kind of visual
marker to indicate the current
page is a good way to do this.
 
  - Interactive:Each link should be big enough
to click on and the appearance
of the link should change when
the user hovers over each item
or clicks on it. It should also
be visually distinct from other
content on the page.
 
  - Consistent:The more pages a site contains,
the larger the number of
navigation items there will be.
Although secondary navigation
will change from page to page,
it is best to keep the primary
navigation exactly the same.



## The ABC of programming:

- A SCRIPT IS A SERI ES OF INSTRUCTIONS:
  - RECIPES:By fo llowing the instructions in a
recipe, one-by-one in the order
set out, cooks can create a dish
they have never made before.
  - HANDBOOKS:Large companies often provide
handbooks for new employees
that contain procedures to fo llow
in certain situations.

  - MANUALS:Mechanics often refer to car
repair manuals when servicing
models they are not familiar
with. These manuals contain a
series of tests to check the key
functions of the car are working,
along with details of how to fix
any issues that arise.

>WRITING A SCRIPT

To write a script, you need to first
state your goal and then list the
tasks that need to be completed in
order to achieve it.

>FROM STEPS TO CODE

Every step for every task shown
in a flowchart needs to be written
in a language the computer can
understand and follow.

**HOW HTML, CSS,
& JAVASCRIPT FIT
TOGETHER**

- CONTENT LAYER:
  - This is where the content of
the page lives. The HTML gives
the page structure and adds
semantics.

>. html files

- PRESENTATION LAYER:
  - The CSS enhances the HTML
page with rules that state how
the HTML content is presented
(backgrounds, borders, box
dimensions, colors, fonts, etc.).

>.css files

- BEHAVIOR LAYER:
  - This is where we can change
how the page behaves, adding
interact ivity. We will aim to keep
as much of our JavaScript as
possible in separate files.

>.js files



