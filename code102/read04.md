### HTML 4 was released in 1997 
### XHTML 1.0 was released in 2000 
> There was also a third version
of XHTML 1.0 called XHTML
1.0 Frameset
#### HTML 5 was released in 2000

# DOCTYPES :
> Because there have been
several versions of HTML, each
web page should begin with a
DOCTYPE declaration to tell a
browser which version of HTML
the page is using

#### HTML 5



#### HTML 4

<!DOCTYPE html PUBLIC
"-//W3C//DTD HTML 4.01 Transitional//EN"
"http://www.w3.org/TR/html4/loose.dtd">

#### Transitional XHTML 1.0

<!DOCTYPE html PUBLIC
"-//W3C//DTD XHTML 1.0 Transitional//EN"
"http://www.w3.org/TR/xhtml1/DTD/
 xhtml1-transitional.dtd">
 
 #### Strict XHTML 1.0
 
 <!DOCTYPE html PUBLIC
"-//W3C//DTD XHTML 1.0 Strict//EN"
"http://www.w3.org/TR/xhtml1/DTD/
 xhtml1-strict.dtd">
 
 #### XML Declaration

<?xml version="1.0" ?>

# Comments in HTML

 < !-- -->

#### example 

![image](https://user-images.githubusercontent.com/44680406/109818279-8028bc00-7c3b-11eb-9572-1fb5cdb7d1ae.png)

# ID attribute 

Every HTML element can carry
the id attribute. It is used to
uniquely identify that element
from other elements on the
page 

#### example

![image](https://user-images.githubusercontent.com/44680406/109818950-3ab8be80-7c3c-11eb-987c-7d1528f81c91.png)


# Class Attribute

Every HTML element can
also carry a class attribute.
Sometimes, rather than uniquely
identifying one element within
a document

#### example 

![image](https://user-images.githubusercontent.com/44680406/109819325-9d11bf00-7c3c-11eb-9bbb-aba856a6268c.png)

# Block Elements

Some elements will always
appear to start on a new line in
the browser window. These are
known as block level elements.

# Inline Elements

Some elements will always
appear to continue on the
same line as their neighbouring
elements. These are known as
inline elements

# Grouping Text & Elements In a Block

 > < div>

The < div > element allows you to
group a set of elements together
in one block-level box 

#### example 

![image](divexample.png)

> < span>

The < span> element acts like
an inline equivalent of the < div>
element. It is used to either:

- Contain a section of text
where there is no other suitable
element to differentiate it from
its surrounding text
- Contain a number of inline
elements

# Iframes

>An iframe is like a little window
that has been cut into your
page 

#### Iframe attributes

>- src : The src attribute specifies the
URL of the page to show in the
frame.
>
>- height : The height attribute specifies
the height of the iframe in pixels.
>
>- width : The width attribute specifies
the width of the iframe in pixels.

# Iformation about your page 

> < meta> The < meta> element lives inside the < head>.
element and contains.
information about that
web page.

# Escape Characters

> Examples
>
> ![image](escape.png)

>&lt;**div**&gt;<br>
it's very usfel to group<br>
together related elements on the page .
>> auther Authors used class or id attributes
to indicate the role of the &lt;**div**&gt;

># HTML5 
>introduces a new set of elements that allow you to divide up the
parts of a page.
>- &lt;**header**&gt; And &lt;**footer**&gt;
>
>  used for :
>>- The main header or footer
that appears<br> at the top or
bottom of every page on the
site
>>- A header or footer for an
individual &lt;article&gt; or
&lt;section&gt; within the page.

>&lt;**nav**&gt;
><br>The &lt;nav&gt; element is used to
contain the major navigational<br>
blocks on the site such as the
primary site navigation.
>

>&lt;**article**&gt;
>The &lt;<article>&gt;element acts as
a container for any section<br> of a
page that could stand alone and
potentially be syndicated.
>

>&lt;**aside**&gt;
>The &lt;aside&gt; element has two
purposes,<br> depending on whether
it is inside an &lt;article&gt;
element or not
>
>- when it's inside 
>>- sit should contain
information that is related to the
article<br> but not essential to its
overall meaning. For example,<br> a
pullquote or glossary might be
considered as an aside to the
article it relates to
>- when it's outside
>>- it acts as a container
for content that is related to
the entire page.<br> For example,
it might contain links to other
sections of the site, <br>a list of
recent posts, a search box, or
recent tweets by the author.

>&lt;**section**&gt;
>
>The &lt;section&gt; element groups
related content together,<br> and
typically each section would
have its own heading.

>&lt;**hgroup**&gt;
>
>The purpose of the &lt;hgroup&gt;
element is to group together<br> a
set of one or more &lt;h1&gt; through
&lt;h6&gt; elements so that they are
treated as one single heading.

>&lt;**figure**&gt;
>
>It can be used
to contain any content that is
referenced from the main flow of
an article (not just images).
>
>example of usage:
>- Images
>- Videos
>- Graphs
>- Diagrams
>- Code samples
>- Text that supports the main
body of an article

>*note That*
>
>Older browsers that do not
know the new HTML5<br> elements
will automatically treat them as
inline elements.<br> Therefore, to
help older browsers, you should
include <br>these line of CSS which states which new
elements should be rendered as
block-level elements

>>- ![image](Css.png)







