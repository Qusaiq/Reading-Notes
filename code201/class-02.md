# HOW A BROWSER SEES A WEB PAGE

> in order to understand how you can change the content of an HTML 
page using JavaScript, you need to know how a browser interprets the 
HTML code and applies styling to it.

*  RECEIVE A PAGE AS 
HTML CODE

* CREATE A MODEL OF 
THE PAGE AND STORE 
IT IN MEMORY

* USE A RENDERING 
ENGINE TO SHOW THE 
PAGE ON SCREEN

*All major browsers use a JavaScript interpreter to translate your 
instructions (in JavaScript) into instructions the computer can follow.*

-----------------

# HOW HTML, CSS, &JAVASCRIP TFIT TOGETHER
----------------------

> How *HTML* and *CSS* fit together with *JavaScrip*

```html
<html>
```
>- CONTENT LAYER 
. html files 
This is where the content of 
the page lives. The HTML gives 
the page structure and adds 
semantics. 

```css
{CSS}
```
>- PRESENTATION LAYER 
. css files 
The CSS enhances the HTML 
page with rules that state how 
the HTML content is presented 
(backgrounds, borders, box 
dimensions, colors, fonts, etc.).

```javascript
javascript()
```
>- BEHAVIOR LAYER 
.js files 
This is where we can change 
how the page behaves, adding 
interactivity. We will aim to keep 
as much of our JavaScript as 
possible in separate files. 

------------

# PROGRESSIVE ENHANCEMENT


These three layers form the basis of a popular 
approach to building web pages called 
progressive enhancement. 

>- *HTML ONLY*
>>Starting with the HTML layer 
allows you to focus on the most 
important thing about your site: 
its content. 
Being plain HTML, this layer 
should work on all kinds of 
devices, be accessible to all 
users, and load quite quickly on 
slow connections.
>- *HTML + CSS*
>>Adding the CSS rules in a 
separate file keeps rules 
regarding how the page looks 
away from the content itself. 
You can use the same style sheet 
with all of your site, making your 
sites faster to load and easier 
to maintain. Or you can use 
different style sheets with the 
same content to create different 
views of the same data
>- *HTML+CSS+JAVASCRIPT*
>>The JavaScript is added last 
and enhances the usability of 
the page or the experience of 
interacting with the site. 
Keeping it separate means 
that the page still works if the 
user cannot load or run the 
JavaScript. You can also reuse 
the code on several pages 
(making the site faster to load 
and easier to maintain)

---------------------

# CREATING A BASIC JAVASCRIPT

> JavaScript is written in plain text, just like HTML and CSS, so you do not 
need any new tools to write a script. This example adds a greeting into an 
HTML page. The greeting changes depending on the time of day. 


```javascript
var today= new Date(); 
var hourNow = today.getHours(); 
var greeting; 
if (hourNow > 18) { 
greeting= 'Good evening!'; 
else if (hourNow > 12) { 
greeting = ' Good afternoon!'; 
else if (hourNow > 0) { 
greeting = 'Good morni ng!'; 
else { 
greeting = 'Welcome! ' ; 
document .write( ' <h3>' +greeting + ' </ h3> '); 
```

------------

# LINKING TO A JAVASCRIPT FILE FROM AN HTML PAGE 


```html
<!DOCTYPE html> 
<html> 
<head> 
<title>Constructive &amp; Co.</ title> 
<link rel ="stylesheet" href="css/ cOl.css" /> 
</ head> 
<body> 
<hl> Constructive &amp ; Co. </hl> 
<script src="js/ add-content.js"></ script> 
<p>For all orders and i nquiries please cal l 
<em>SSS-3344</ em></ p> 
</ body> 
</html>  
```

---------------


# THE SOURCE CODE IS NOT AMENDED 

> If you look at the source code for the example 
you just created, you will see that the HTML is 
still exactly the same.

--------------
# LACING THE SCRIPT IN THE PAGE 

```html
!DOCTYPE html > 
<html > 
<head> 
<title>Constructive &amp; Co.</title> 
<li nk rel ="stylesheet" href="css/ cOl . css" / > 
</ head> 
<body> 
<hl>Constructive &amp; Co.</hl> 
<script>document.write(' <h3>Welcome !</h3>'); 
</script> 
<p>For all orders and inquiries please call 
<em>555-3344</ em></ p> 
</body>
</html>
```

----------------------

# HOW to use object and methods 

```javascript
document.write( ' <h3>' +greeting + ' </ h3> ');

```

> document is the object 

> the dot * (.) * is the member operator

> ```html ('<h3>' +greeting + '</h3>')``` is the parameters

>```html write( ' <h3>' +greeting + ' </ h3> ');``` is the method


---------------------

# CROSS-SITE SCRIPTING (XSS) ATTACKS

>if you add HTML to a page using i nnerHTML (or several jQuery methods), 
you need to be aware of Cross-Site Scripting Attacks or XSS; otherwise, 
an attacker could gain access to your users' accounts. 

-----------

># HOW XSS HAPPENS XSS involves an attacker placing malicious code into a site. Websites often feature content created by many different people. For example: 

- Users can create profiles or add comments
-  Multiple authors may contribute articles
XSS involves an attacker placing malicious code into 
a site. Websites often feature content created by 
many different people. For example: 
-  Data can come from third-party sites such as 
Facebook, Twitter, news tickers, and other feeds
-Files such as images and video may be uploaded 

