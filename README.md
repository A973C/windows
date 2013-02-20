# windows

---

#### a handy, loosely-coupled jQuery plugin for full-screen scrolling windows

## Usage

Include the latest jQuery and `assets/js/jquery.windows.js` in your HTML page.

#### js

```javascript
$(document).ready(function(){

    $('.window').windows({
        snapping: true,
        snapSpeed: 500,
        snapInterval: 1100,
        onScroll: function(scrollPos){
            // scrollPos:Number
        },
        onSnapComplete: function($el){
            // after window ($el) snaps into place
        },
        onWindowEnter: function($el){
            // when new window ($el) enters viewport
        }
    })

});
```

## In the Wild

* [Example Site](http://nick-jonas.github.com/windows)
