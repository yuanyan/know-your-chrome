# Kown your chrome

## Chrome 新特性演示

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

> Blink and WebKit use a compositor to display web contents to the user's screen. But how do we take a render tree (the browser's internal representation of a web page) and display it using a compositor? How do we decide what content should have a separate compositing layer, and how does compositing benefit us? In this presentation, Chrome software engineer Shawn Singh will introduce basic concepts of compositing, and then we will focus on how Blink bridges the gap between the render tree and the compositor. This is only a slice of the overall rendering architecture, but it will be fun and insightful for any web developers and browser developers with an interest in how Blink and WebKit render web pages.

* [WebComponents are the Future](http://www.youtube.com/watch?v=eJZx9c6YL8k)

> Web Components are going to fundamentally change the way we think, build, and consume web apps. ShadowDOM, Mutation Observers, custom elements, MDV, Object.observe(), CSS. How does it all fit together?
> This session will prepare you for the future of the web platform by discussing the fundamentals of web components and how we can use them today with frameworks like AngularJS.

## 文章
* [How Browsers Work: Behind the scenes of modern web browsers](http://www.html5rocks.com/en/tutorials/internals/howbrowserswork/)  [中文](http://www.html5rocks.com/zh/tutorials/internals/howbrowserswork/)
* [理解WebKit和Chromium](http://www.ituring.com.cn/minibook/705)
