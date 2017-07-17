# udacity-fend-optimization

### What is this?

This a project for Udacity Front-end Nanodegree. My mission is to optimize the given app. You can try the live demo [optimized mobile portfolio](https://iamzhaihy.github.io/udacity-fend-optimization/), and copy the link to [Pagespeed Insight](https://developers.google.com/speed/docs/insights/about)




### pt 1. Pagespeed Score
The goal is to get a score higher than 90 on both mobile and desktop. 

#### Here are changes that I made
- made images offline
- optimized `pizzeria.jpg`
- move all `<script>` to bottom
- set media `print` of `print.css`
- minified & inline `style.css`
- minified `perfmatters.js`
- use `async` when loading external js




### pt 2. 60 frames per second
The goal is to optimize `main.js` so the app can run at 60 fps

#### Here are changes that I made
- optimized code structure in `changePizzaSizes()`
- optimized code structure in line 474-479
- use faster `getElementsByClassName()` in line 510
- optimized code structure in `updatePositions()`
- optimized the event listener (line 533-555)




### How to run it?
All you need is to do is:

1. Uncompress the zip file
2. Locate the *index.html* file
3. Right click and open it with your favorite browser.
   (Or you can just drag it to a running browser)




### Online Resources 
- [CSS Minifier](https://cssminifier.com/)
- [JSCompress](https://jscompress.com/)



### Notice

1. All the things you need is in the compressed file. If the file was damaged or corrupted, you can find a copy on my Github.
2. I will add more features to this map after I learn more about using framework and APIs.
