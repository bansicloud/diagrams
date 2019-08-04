# diagrams
Draw a geometry problem easily with Easy Graphing! You don't even need to know javascript very well! It uses the Cartesian Coordinate System (the normal one), which is much simpler than the javascript coordinates! <br>
An example with comments:
http://kiraprograms.com/diagramsHowTo.js.<br>
Use this by downloading it, or use this line: http://kiraprograms.com/diagrams.js

Here are some things that you can do:
Change the pixel size: <br>
`size(the new size in pixels)`<br>


Change the center of the screen. Now the center of the screen is the point (1,1), by default it is 0,0.<br>
`changeCenter(the x position that you want in the center of the screen, y position);`<br>

Draw the Axis: <br>
`axis();`<br>

Make a vertex:<br>
`var b = new vertex(x position, y position, optional color);`<br>

Draw and label the vertex:<br>
`b.label(what you want to label it as, optional direction);`<br>
Or, just label the coordinates: <br>
`b.labelCoords(optional direction);`<br>

Create a regular polygon (returns a list of vertecies that need to be connected and drawn)<br>
`var pentagon = makeRegularPolygon(number of points, vertex in the center, the distance between 2 points);`<br>

Create a line (with at least 2 points):<br>
`var eabc = new line([list of the vertecies in the line], optional width, optional color);`<br>

Draw a line/ polygon/ circle:<br>
`eabc.draw();`<br>
