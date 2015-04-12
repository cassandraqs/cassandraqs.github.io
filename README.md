### Getting started

#### Part 1:
* Open [this](http://cassandraqs.github.io) in your browser.
* Paste cassandraqs.github.io into [Google Pagespeed Insights](https://developers.google.com/speed/pagespeed/insights/) to check score.

##### Optimizations:
1. Reduced image size of pizzeria.jpg to 180 x 135.
2. Removed external google font link and this doesn't mess up the style.
3. Inlined style.css.
4. Added media="print" to print.css link.
5. Added async to GoogleAnalytics script tag.

#### Part 2:
* Click on "Cam's Pizzeria" in the homepage.
* Open developer tools and check in the console.
* Slide the resize radio to see the time needed for resizing.
* Scroll down the page to see the average time to generate last 10 frames.

##### Optimizations:
1. Cached document.querySelectorAll(".randomPizzaContainer") so that it won't be recalculated each time you go through the loop;
2. Cached document.querySelectorAll('.mover') so that it won's be repeated every time updatePositions() is called.
3. Since there are only five possible values of phase, I have calculated and stored them in cachedPhase also.
4. Made changes to generate 150 sliding pizzas and update their positions for each frame.
