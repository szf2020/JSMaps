# Use any .png or .jpg image to convert into a javascript annotable file/map.

https://medium.com/@gautamtata/build-and-add-ui-events-to-your-own-maps-6ec83bbd8d3 for a simple tutorial

The purpose of this project was to implement a tool that lets users build maps which are interactive and usable from plain SVG data.

**HOW TO USE**
1. Have the SVG file for the map you want to build. 
    If you have the map in png/jpeg you can convert it to SVG here : https://image.online-convert.com/convert-to-svg

2. From the homescreen, navigate to SVG to JvectorMap. 

    Give the elements an Id and a name and paste your svg into the textbox.
    Click on convert to map and you should have your svg converted into JvectorMap.

3. Copy the code from the JvectorMap and replace it with in the file vectorMap.js.
    **Make sure to change the word paths to pathes in line 5**
4. Basic annotations can be made in the file jquery.vmap.js

Examples of events here : Hover Color, Background Color, Show-Tooltip, Zoom and normalizeFunction.

**Interaction Features**
--Scroll wheel zoom
--Double click zoom
--Zoom to area 
--Keyboard navigation
--Events: click, mouseover, etc.
--Marker dragging

**Visual Features**
--Zoom animation
--popup fade animation
--Very nice default design for markers

**Customization Features**
--Pure CSS3 popups and controls for easy restyling
--Image- and HTML-based markers
