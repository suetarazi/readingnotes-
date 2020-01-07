
# HTML/CSS - Chapter 2 Notes: 
HTML elements can be used to describe the structure of the page such as headings and paragraphs. Some examples of tags that identify structure are: 
```
<h1> <h2> <h3> <h4> <h5> <h6> are different sizes of headings (largest to smallest)
<b> bold
<i> italicize
<sup> superscript
<sub> subscript
<p> paragraph
```

Other HTML elements are used to for semantic markup, which serve to describe where emphasis may be placed, things in quotes, etc. Some examples are:
```
<strong> item of importance
<em> item of emphasis
<blockquote> quote that takes an entire paragraph
<q> shorter quote
<abbr> abbreviation
<cite> citation
<dfn> definition
<address> address
<ins> insertion
<del> deletion
<s> something that is no longer accurate, but should not be deleted
```

# HTML/CSS - Chapter 10 Notes:

CSS associates rules for style with HTML. Each CSS rule has two parts: a selector and a declaration. The selector refers to the HTML portion being referenced and the decleration is the style rule being applied. Each declearation is then made of two parts: a property and a value. 

``` 
h3 {
  font:size = 20px;
  }
  
 ```
 
 Best practices state CSS rules be stored in a separate file (externally) and referenced in the head of the HTML document via a <link> tag.
 
# JavaScript - Chapter 2 Notes:

JavaScript code is organized into Statements, each which starts on a new line. Groups of statements can be organized into blocks of code. Comments in JavaScript are important (so one knows what you are doing) and are denoted by /* and */ for multi-line comments and // for a single line comment.

Variables are used to store data. They are declared using the term var followed by the variable name followed by a value (if you choose to assign one). 

JavaScripts accepts data that is numerical (integers or decimals), strings (text data denoted in single quotes) and booleans (true or false). An array stores a list of values. 

JavaScript is used to evaluate expressions into a single value using operators such as +, -, / and *.

# Javascript - Chapter 4 Notes: 

There are two components that make up a decision: 1. the evaluation of a condition and 2. a conditional statement that says what to do.

There are conditional statements such as: 
``` 
== is equal to
!= is not equal to
=== strict equal to 
!== strict not equal to
> greater than
< less than
>= greater than or equal to 
<= less than or equal to
&& logical and operator - used when you need two or more conditions to be met
|| logical or operator - used when you need one or another condition met
! logical not
```

If else statements checks for conditions to be met. If the first condition is met, then the if portion is satisfied and that portion of the code is executed. If it is not met, then the else portion of the code is executed.




