# Kown your chrome

## Chrome 新特性示例

* [HTML5 DEMOS](https://html5-demos.appspot.com/)


## Blink 实现规划

* [Blink "Intent" emails](https://docs.google.com/spreadsheet/ccc?key=0AjGgk26K1Cc-dEIySWlPNmFHMWlCUGxIQkstZXJ3clE#gid=0)

## Chrome 源码解析

* [Blink 源码解析](https://github.com/yuanyan/kownyourchrome/tree/master/Blink)
* [V8 源码解析](https://github.com/yuanyan/kownyourchrome/tree/master/V8)

## W3C 新规范
* [Shadow DOM](https://dvcs.w3.org/hg/webcomponents/raw-file/tip/spec/shadow/index.html) 
  * DOM & style encapsulation boundaries
* [Custom Elements](https://dvcs.w3.org/hg/webcomponents/raw-file/tip/spec/custom/index.html)
  * create new HTML elements - expand HTML's existing vocabulary
  * extend existing DOM objects with new imperative APIs
* [HTML Templates](https://dvcs.w3.org/hg/webcomponents/raw-file/tip/spec/templates/index.html)
  * inert chunks of clonable DOM. Can be activated for later use (e.g. MDV)  
* [HTML Imports](https://dvcs.w3.org/hg/webcomponents/raw-file/tip/spec/imports/index.html)

  ```html
  <link rel="import" href="x-foo.html">
  ```
* [Web Animations](https://dvcs.w3.org/hg/FXTF/raw-file/default/web-anim/index.html)
* [User Timing](http://w3c-test.org/webperf/specs/UserTiming/)
* [Resource Timing](http://www.w3.org/TR/2011/WD-resource-timing-20110524/)
* [CSS Variables Module Level 1](http://dev.w3.org/csswg/css-variables/)

  ```css
  :root {
    var-main-color: #06c;
    var-accent-color: #006;
  }
  /* The rest of the CSS file */
  #foo h1 {
    color: var(main-color);
  }
```
* [CSS Fonts](http://dev.w3.org/csswg/css-fonts/)
* [CSS Flexible Box Layout Module](http://dev.w3.org/csswg/css-flexbox/)

## Chrome 新特性
* [Lazy block layout](https://docs.google.com/document/d/1-tbcMJV8wNbX2g5ehNIcE_1W7Kj_B3g9w1BrUgHnh3U/edit)
* [Moving DOM Attributes to JavaScript Prototype Chains](https://docs.google.com/document/d/1jwA8mtClwxI-QJuHT7872Z0pxpZz8PBkf2bGAbsUtqs/edit#)

## 视频
* [Compositing in Blink and WebKit](http://www.youtube.com/watch?v=Lpk1dYdo62o)

## 文章
* [How Browsers Work: Behind the scenes of modern web browsers](http://www.html5rocks.com/en/tutorials/internals/howbrowserswork/)
