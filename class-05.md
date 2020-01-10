# Class 05 Reading Notes:

## HTML Chapter 5 - Images
``` The <img> tag is used to add an image. Usually are .jpg or .gif files. 
The syntax: <img src="images/suesSurfboard.jpg" alt="description" title="Add'l info" width="100", height="250", align="left" />
```
Images can be placed in block format or inline.  

Three rules for images:
1. save them in the right format
1. save them in the right size
1. use the correct resolution

Can also have animated gif files that show several frames in sequence. It is simple animation. 
```
<figure> allows for several images to be placed inside it. 
<figcaption> allows for a caption to be included that describes the figure.
```

## CSS Chapter 11 - Color

3 ways to specify color: RGB values, HEX codes, color names.
background-color: specifies background color. 

CSS3 also allows us to specify opacity which is the A in RGBA. 

CSS3 allows us to choose a color based on hue (the color), saturation (the amount of gray in a color), and lightness a.k.a. luminosity (the amount of black or white in a color). This is abbreviated as HSL.

Contrast between text and background is important, so that your text is readable. 

## CSS Chapter 12 - Text

Two general ways to affect text:
1. Directly - typeface ex. bold, italics; and size. 
1. Globally - effects such as color and spacing that affect the whole document regardless of font. 

Font types:
1. serif - have feet
1. san serif - no feet - easy to read
1. monospace - used to code because it lines up nicely

Font weight: adds emphasis (bolding)
Font style: normal vs italic vs oblique
Font stretch: how far apart or smushed together the letters may be

Specifying typefaces: font-family, font-size (can be specified in px, percentages or EMS) 

Changing from uppercase to lowercase: text-transform: lowercase;
Changing from lowercase to uppercase: text-transform: uppercase;
Changing to all caps: text-transform: capitalize;

Text decoration: underline, overline, line-through, blink (animates text)

Text-align - used to move text left, right, center

Text-indent - indents your text
