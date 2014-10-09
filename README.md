BillBoard-Slider
================

#### A slider that uses CSS3 and jQuery to make a billboard flipper slider 

###### Usage:
```javascript
   $('.billboard-rotater').billboard({
    colWidth: 30, // For Speed and optimizations ** set '100%' to make it as one cube.
    transitionSpeed: 1, // Accepts decimal numbers and int Numbers
    transitionDelayMultiplier: .1, // Delay between columns to show the BillBoard Effect , set to 0 to Disable it.
    optimizeOutput: true, // to Remove repating columns background , set to false if you want to show the columns
    dimensionalOutput: 'cube', // accepts string 'cube' or 'flat' ; flat will only show the first two images one for each of the flat columns
    billCallBack: function () { }// Call back function runs right after the plugin finishes constructing itself
   });
 ```  
   
   
