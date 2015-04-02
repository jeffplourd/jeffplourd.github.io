## Website Performance Optimization portfolio project

To run this application, go to "http://jeffplourd.github.io/"

This application represents a variety of performance optimization techniques.

In the 'index.html' document, I performed the following optimizations:
-added meta tag to ensure proper viewport upon initial load
-used font loader to reduce Google Fonts load time
-inlined primary css and placed "print" css in separate folder (used media attr to make it non-renderblocking)
-changed all script tags to async to avoid render blocking
-resized all images to reduce load time

In the "resizePizzas" function in "main.js", I performed the following optimizations:
-removed unnecessary computations in the for loop
-switched each instance of "querySelectorAll" to "getElementsByClassName"

In the "updatePositions" function in "main.js", I performed the following optimizations:
-switched each instance of "querySelectorAll" to "getElementsByClassName"
-removed unnecessary calculations from for loop

In the inital loading function in "main.js", I performed the following optimizations:
-reduced the number of pizza images being produced from '100' to '32'

In the "views/css/style.css" document, I added the following optimizations:
-added "backface-visibility: hidden" hack


While completing this project, I refered to the following articles:
-http://calendar.perfplanet.com/2013/the-runtime-performance-checklist/
-http://www.html5rocks.com/en/tutorials/speed/scrolling/
-http://compressjpeg.com/
-articles from Google's PageSpeed Insights