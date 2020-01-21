# Charts and Graphs
## Chart.js
- this is a plug-in that uses HTML5's Canvas element to create charts and graphs
- need to download chart.js
- graphs can be line, bar or pie types


## Canvas
- canvas uses the ``` <canvas> ``` tag and has the option to specify width and height
- it requires a closing tag!
- it has a rendering method called getContext()

- uses coordinate space with 0,0 starting in the top left corner
- can use fill, stroke or clear preceeding the shape name
- for rectangle: specify (x, y, width, height)
- can use a path to draw any other shape. Ex. triangle: 
``` ctx.beginPath();
    ctx.moveTo(x,y);
    ctx.lineTo(x,y);
    ctx.lineTo(x,y);
    ```
- can also do curves, lines, Beziers and quadratics

- can do fill or transparent
- can change line weight
- can do gradiants, create patterns and shadows

- can also style text
