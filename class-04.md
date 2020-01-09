# Class 04 Reading Notes

## HTML Ch 4: Links
Links can be:
1. to an external website
1. from one page to another on the same site
1. from one part of a page to another part of the same page using 
```
<a href="#name of section">stuff user clicks on</a> then later down the page <h3 id="name of section">
```

1. to an email program using mailto:

Links can also open in a new browser or tab

Links follow the syntax:
```
<a href="http://www.nameofwebsite.com">Link the User Clicks On</a>
```
Relative links link within the same site. We can go forwards for backwards. Examples:
```
<a href="reviews.html">This jumps to a page in the same folder</a>
<a href="catfood/brands.html">This jumps to a page in a child folder folder</a>
<a href="..index.html">This jumps to a folder above the current location</a>
<a href="../../index.html">This jumps to a page two folders up</a>
```

## CSS Ch 15: Layout
Layout controls where each element sits on a page. 
```
<div> tag is used to create sections in layout. 
```
Can have block level elements or inline elements. 
Can also have blocks within a block: child blocks in a parent block. 

4 ways to position elements:
1. normal flow - what browsers default to unless otherwise specified
1. relative positioning - shifts an element up, down, L or R
1. absolute positioning - content moves as the user scrolls up or down
1. float - moves content L or R. need width to be defined. Can be used in multi-column layouts. 

Fixed width layouts vs Liquid a.k.a. 'stretchy' layouts

Using grids

## JavaScript - Ch 3: Functions, Methods & Objects:
Function = a series of statement that perform a specific task. 
Method = functions that exist inside of an object.
Objects = made up of properties and methods; used to create models

## Pair Programming article:

### What it is: two developers working together at a single terminal. Two roles: 
1. Driver - the programmer who has their hands on the keyboard
2. Navigator - uses their words to guide the driver, provide algorithms and help with debugging

### 4 skills needed to learn and pair programming does all of these:
1. listening
1. speaking
1. reading 
1. writing

### 6 Reasons Why its Good:
1. Greater efficiency
1. Engaged collaboration
1. Learning from colleagues
1. Social skills
1. Job interview readiness
1. Work environment readiness