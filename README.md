jQBezier
========
jQuery Plugin for drawing bezier curves between html elements. Especially good for showing parent/child relations or tree style diagrams.<br />
Thanks to some random dude's javascript on jsFiddle, I've tidied it up and made it into a jQuery plugin.<br />&nbsp;<br />
Markup
======
Give parent elements an ID and a classname. Give child elements a class naming each ID of the parent. Ie, if your child has parents with ID's box15 and box7, then the child element should have:
```html
<div class="box15 box7">blah</div>
``` 
Usage
=====
```javascript
$('.parent-class').bezier({options});
```
Default Options
=======
```javascript
strokeColor : '#999',  // use 'rainbow' for different coloured lines
strokeWidth : 2,
opacity : 1,
fill : 'none',
animate : true,
animationDirection : 'right',
animationDuration : 0.75
```
Demo
====
See <a href="http://jsbin.com/judodo/1/edit?html,output" target="_new">HERE</a> for a live preview.

