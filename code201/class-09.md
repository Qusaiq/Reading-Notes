# Forms and JS Events


### ***Forms***

- Whenever you want to collect information from visitors you will need a form, which lives inside a <form> element.
- Information from a form is sent in name/value pairs.
- Each form control is given a name, and the text the user types in or the values of the options they select are sent to the server.
- HTML5 introduces new form elements which make it easier for visitors to fill in forms.

##### The ```<form>``` Element
The HTML ```<form>```  element is used to create an HTML form for user input, where it work as container for different types of input elements, *such as: text fields, checkboxes, radio buttons, submit buttons, etc.*
```
<form>
form elements
</form>
```

##### The ```<input>``` Element

- The HTML ```<input>``` element is the most used form element.
- An ```<input>``` element can be displayed in many ways, depending on the type attribute.


### ***Lists***

- List markers can be given different appearances using the list-style-type and list-style image properties.
- Table cells can have different borders and spacing in different browsers, but there are properties you can use to control them and make them more consistent.
- Forms are easier to use if the form controls are vertically aligned using CSS.
- Forms benefit from styles that make them feel more interactive.

#### **How to style forms with CSS**
The easiest way to select input elements is to use CSS attribute selectors.
```
input[type=text] {
  // input elements with type="text" attribute
}
input[type=password] {
  // input elements with type="password" attribute
}
```
These selectors will select all the input elements in the document. If you need to specify any selectors, you’ll need to add classes to the elements.
```
<input type="text" class="signup-text-input" />
```
Then:
```
.signup-text-input {
   // styles here
}
```

### ***Events***

- Events are the browser's way of indicating when something has happened (such as when a page has finished loading or a button has been clicked).
- Binding is the process of stating which event you are waiting to happen, and which element you are waiting for that event to happen upon.
- When an event occurs on an element, it can trigger a JavaScript function. When this function then changes the web page in some way, it feels interactive because it has responded to the user.
- You can use event delegation to monitor for events that happen on all of the children of an element.
- The most commonly used events are W3C DOM events, although there are others in the HTMLS specification as well as browser-specific events.

**When JavaScript is used in HTML pages, JavaScript can "react" on these events.**

#### HTML Events
*An HTML event can be something the browser does, or something a user does.*

Here are some examples of HTML events:

- An HTML web page has finished loading
- An HTML input field was changed
- An HTML button was clicked
- Often, when events happen, you may want to do something.

**JavaScript lets you execute code when events are detected.**

**HTML allows event handler attributes, with JavaScript code, to be added to HTML elements with**

1. Single quotes:
```
<element event='some JavaScript'>
```

2. Double quotes:
```
<element event="some JavaScript">
```
***Note*** In the following example, an onclick attribute (with code), is added to a ```<button>``` element:

Example;

```
<button onclick="document.getElementById('demo').innerHTML = Date()">The time is?</button>
```