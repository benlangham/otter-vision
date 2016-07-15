Reality Filter
========

A demo showing how to use HTML5, JavaScript, WebGL and Google Cardboard to create a manipulated view of the world around you via your phone's front camera.

If you make something brilliant from this code, please do let me know! I'm on Twitter at @thatpatrickguy, or you can find me at http://www.patrickcatanzariti.com.

PatCat


Followed this
https://www.sitepoint.com/filtering-reality-with-javascript-google-cardboard/

Added Sobel filter
https://www.npmjs.com/package/sobel

Chrome console said replace PlaneG with PlaneBufferG

Got this error:
RENDER WARNING: there is no texture bound to the unit 0 Stack Overflow suggested old version of three.js
Downloaded latest


8,388,607 pieces of data in an array (integers from 0-255) for each frame.
Want to reduce resolution of the image - ideally when captured from the camera

Changed capture size (did not work)
http://www.html5rocks.com/en/tutorials/getusermedia/intro/

Changed percentage from 100 to 15 - worked.