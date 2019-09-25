# SplitFlap
Responsive split-flap library
[view demo](https://codepen.io/broregard/pen/vroJzR)

### How to use
```html
<div id="sf-con"></div>
```


```javascript
let sf = new SplitFlap({
  container: document.querySelector("#sf-con"),
  mode: "text",                // text, clock, countdown
  
  speed: 150,                  // ms
  reverseAnimation: true,

  countDown: Date("July 4, 2020 01:23:45"),
  countDown: Date.now() + 1000 * 12,

  text: ["chiang mai", "bangkok", "phuket"],
  textResume: 2500,            // ms
  
  textColor: "70,70,70",       // override RGB
  flapColor: "255, 255, 255",  // override RGB
});
```
