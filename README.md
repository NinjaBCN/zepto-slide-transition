Zepto Slide Transition
======================

The Zepto Slide Transition plugin add to Zepto.js the functions bellow :
- slideDown();
- slideUp();
- slideToggle();

# Requirement

Like a jQuery plugin, this Zepto plugin needs Zepto to work. You can download Zepto at this adress http://zeptojs.com or find its repository here : https://github.com/madrobby/zepto.

N.B. You can't use Zepto with jQuery, it's one or the other.

# How to use

- You need to add the following to your page in your ```<head></head>``` or in your ```<body></body>```, just before the ```</body>```.

```html
<script src="zepto.min.js"></script>
<script src="zepto-slide-transition.js"></script>
```

- Then just use the slide function like you can use it with jQuery :

```javascript
$('element').slideUp();
$('element').slideDown();
$('element').slideToggle();
```
