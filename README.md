# canvas-shaded-relief

Demo of simple shaded relief in the browser with javascript and canvas, more or less copied from [experiments I did in Flash](http://andywoodruff.com/blog/shaded-relief-in-as3/) some years back. (The math is explained in that post.) It takes a grayscale DEM image, calculates luminance pixel-by-pixel, and draws the resultant shaded relief along with some hypsometric tints to new canvas element. Code is all in index.html.

[Here, look, it totally works.](http://awoodruff.github.io/canvas-shaded-relief/)

It's not really useful (slow for images much larger than this), but it's kind of fun!

Input:
![](https://raw.githubusercontent.com/awoodruff/canvas-shaded-relief/gh-pages/molokai.png)

Output:
![](https://raw.githubusercontent.com/awoodruff/canvas-shaded-relief/gh-pages/molokai-relief.png)
