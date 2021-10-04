# Forms

- Form Structure

  - Form controls live inside a
    < form> element. This element
    should always carry the action
    attribute and will usually have a
    method and id attribute too.

- text input

  - The < input> element is used
    to create several different form
    controls. The value of the type
    attribute determines what kind
    of input they will be creating.

- type="text"
  When the type attribute has a
  value of text, it creates a singleline
  text input.

- **name:**
  When users enter information
  into a form, the server needs to
  know which form control each
  piece of data was entered into.
  (For example, in a login form, the
  server needs to know what has
  been entered as the username
  and what has been given as the
  password.) Therefore, each form
  control requires a name attribute.
  The value of this attribute
  identifies the form control and is
  sent along with the information
  they enter to the server.

- **Password Input**

  - type="password"
    When the type attribute has
    a value of password it creates
    a text box that acts just like a
    single-line text input, except
    the characters are blocked out.
    They are hidden in this way so
    that if someone is looking over
    the user's shoulder, they cannot
    see sensitive data such as
    passwords.

  - **name**
    The name attribute indicates
    the name of the password input,
    which is sent to the server with
    the password the user enters.

- **radio**:Radio buttons allow users to pick
  just one of a number of options.

  - **name**
    The name attribute is sent to
    the server with the value of the
    option the user selects. When
    a question provides users with
    options for answers in the form
    of radio buttons, the value of
    the name attribute should be the
    same for all of the radio buttons
    used to answer that question.

  - **value**
    The value attribute indicates
    the value that is sent to the
    server for the selected option.
    The value of each of the buttons
    in a group should be different
    (so that the server knows which
    option the user has selected).

- Submit Button

  - **name**
    It can use a name attribute but it
    does not need to have one.

  - **value**
    The value attribute is used to
    control the text that appears
    on a button. It is a good idea to
    specify the words you want to
    appear on a button because the
    default value of buttons on some
    browsers is ‘Submit query’ and
    this might not be appropriate for
    all kinds of form.

## Lists, Tables and Forms

- Labels for form elements are
  often different lengths, which
  means that the form controls will
  not appear in a straight line. This
  is demonstrated in the example
  on the right (without CSS applied
  to the form controls).
  In this form, each topic we ask
  the user about is placed inside
  a < div> element to ensure that
  each question appears on a new
  line. It is easier for users to fill in
  a form if the form controls are
  aligned in a straight vertical line.
  The CSS on the opposite page
  addresses this.
  If you look at where we ask
  users their gender, the two
  radio buttons each have their
  own < label> (one saying male
  and another saying female). A
  < span> element has been added
  to the title which.

- **cursor**

  - The cursor property allows
    you to control the type of mouse
    cursor that should be displayed
    to users.
    For example, on a form you
    might set the cursor to be a hand
    when the user hovers over it.
    Here are the most commonly
    used values for this property:

- You should only use these values
  to add helpful information for
  users in places they would
  expect to see that cursor. (For
  example, using a crosshair on a
  link might confuse users because.

### EVENT

- Here is a selection of the events that occur in the browser while you are
  browsing the web. Any of these events can be used to trigger a function
  in your JavaScript code.

- HOW EVENTS TRIGGER JAVASCRIPT CODE:

  - When the user interacts with the HTML on a web page, there are three
    steps involved in getting it to trigger some JavaScript code.
    Together these steps are known as event handling.

- TRADITIONAL DOM EVENT HANDLERS:

  - All modern browsers understand this way of creating an event handler,
    but you can only attach one function to each event handler.

- EVENT LISTENERS

  - Event listeners are a more recent approach to handling events.
    They can deal with more than one function at a time
    but they are not supported in older browsers.

![qq](https://cdn.tutsplus.com/active/uploads/legacy/flashtuts/074_EventListenersBasics/2.jpg)

- FORM EVENTS

  - There are two events that are commonly used with forms.
    In particular you are likely to see submit used in form validation.

- HTLS EVENTS

  - Here are three page-level events that have been
    included in versions of the HTMLS spec that
    have become popular very quickly.
