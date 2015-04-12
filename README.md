### Getting started

#### Part 1:
* Open [this](cassandraqs.github.io) in your browser.
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
* Scroll down the page to see the average time to generate last 10 frames.

##### Optimizations:
1. Made changes to generate 20 random pizzas when page loads.
2. Made changes to generate 150 sliding pizzas and update their positions for each frame.
