
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
 
 
