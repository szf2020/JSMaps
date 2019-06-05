# Use any .png or .jpg image to convert into a javascript annotable file/map.

https://medium.com/@gautamtata/build-and-add-ui-events-to-your-own-maps-6ec83bbd8d3 for a simple tutorial

1. Convert your .png or jpeg/.jpg image to a .SVG extention.
2. Get the source code of your SVG: I used this great online tool http://editor.method.ac/ to get the source code.

3. Another great tool available is the svg to Vectormap source code converter. Using this tool it is possible to get the VectorMap code online : http://svg.wangxingrong.com/
//copyrights wangxingrong

Jquery.VectorMap.js is responsible for the structural design of the map. It annotates nodes as *paths* from an .SVG file and gives a vecotor map which is annotatable using JS. Replace my code with your source code obtained from (http://svg.wangxingrong.com/).

jquery.vmap.js is responsible for events on the map such as Zoom, highlighting, colors and Click events such as mouseOver and click. The default params function which gives basic instructions for map events is implemented with changes such as name of map and path names as defined in jQueryVectorMap.js

