# MiniWebCarousel
Minimalistic image carousel using pure css and js. No dependencies.

Features:
* Autoplay
* Next and previous buttons
* Quick-Change-Buttons
* Based on Divs, any content can be put into the carousel
* No dependencies
* Minimalistic setup requirements

How to use: once you've checked the code (Always check code even if it is open source) and want to use it, switch to the minified branch and download it. Add the js and css folder to your project. The carousel itself in html is quite basic, checkout the included html and use it as a template. In your own html (or whatever) include the css and at the end of the body the js. After you include the js, also add a call SetupCarousels. There is an example provided in the html file, but here is the one-liner anyway:
```
<script type="text/javascript">SetupCarousels(500,5000);</script>
``` 
This setups all carousels on this page with a display time of 5000ms and a transition time of 500ms.

To change the style of the carousel, work through the css file. Only the quick-change-button is colored in js (currently) so it properly fades in and out. Look for an rgba value in the js if you want to change it.

There is also a demo branch where multiple carousels are included in one page. Two of them as divs, two as iframes.
