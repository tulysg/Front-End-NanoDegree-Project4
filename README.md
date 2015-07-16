To view the portfolio project click here.

http://tulysg.github.io/Front-End-NanoDegree-Project4/

####Part 1: Optimize PageSpeed Insights score for index.html

1. Optimized image pizzeria.jpg from W: 2048px, H:1536 px to a new size of W: 100px, H: 75px for index.html page.
2. Customized image, title, header and email address on index.html.
3. async was added to google analytics script.
4. On css/print.css link, media="print" was added so that it loads only when print command is given.
5. On index.html, moved the google webfont link at the end of the page.
6. minified and inlined style.css file.
7.Created pizzeria-big.jpg for pizza.html page so that  index.html has only small  size jpg .

To view pizza.html click here.

http://tulysg.github.io/Front-End-NanoDegree-Project4/views/pizza.html

####Part 2: Optimize Frames per Second in pizza.html.

The following changes were made to views/js/main.js 

1. On document. addEventListener, looped through 32 instead of 200 pizza. 
2. On function changePizzaSizes, changed querySelectorAll with getElementsByclassName and moved the variables from for loop to outside of loop.
3. Changed all querySelector to getElementById for performance improvement.
4. Created a new function NewPizza() to generate random pizzas and appends all the pizzas only once ;
5. Moved document.body.scrollTop outside of the for loop in updatePositions function;
6. Added will-change: transform on style.css.


### Useful links:

* [Optimizing Performance](https://developers.google.com/web/fundamentals/performance/ )
* [Analyzing the Critical Rendering Path](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/analyzing-crp.html )
* [Optimizing the Critical Rendering Path](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/optimizing-critical-rendering-path.html )
* [Avoiding Rendering Blocking CSS](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/render-blocking-css.html)
* [Optimizing JavaScript](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/adding-interactivity-with-javascript.html )
* [Measuring with Navigation Timing](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/measure-crp.html )
*[The fewer the downloads, the better](https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/eliminate-downloads.html)
*[Reduce the size of text](https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/optimize-encoding-and-transfer.html)
*[Optimize images](https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/image-optimization.html)
*[HTTP caching](https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/http-caching.html)
* http://www.imageoptimizer.net/Pages/Home.aspx