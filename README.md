# jQuery Pie-Loader

A lightweight jQuery plugin to animate a SVG pie loader

### Demo page

<a href="http://codepen.io/toplefty/pen/OMxGVx?editors=0110">http://codepen.io/toplefty/pen/OMxGVx?editors=0110</a>

### Installation

Include script after the jQuery library:

```html
<script type="text/javascript" src="/path/to/jquery-pie-loader.js"></script>
```
Recommended : use the scss file and customize easily your pie colors.

Alternatively you can include the css 
```html
<link rel="stylesheet" href="/path/to/jquery-pie-loader.css"></script>
```

### Usage

```html
<figure id="my-item" class="pie-loader"></figure>
```

```js
$('#my-item').pieLoader( options )
```

### Options

#### easing (string)

An optional parameter to specify the animation easing. Defaults to easeOutCubic.

```js
easing: 'swing'
```

#### duration (number)

An optional parameter specifying the length of the animation in milliseconds (ms). Defaults to 2000 (2 seconds).

```js
duration: 2000
```

#### dimension (number)

This parameter specifies the dimension of the pie, in pixels. Defaults to 200px

```js
dimension: 300
```

#### percentage (number)

The final value that you want the pie to be animated to.

```js
percentage: 42
```

#### onStart (function)

A function to be called when the animation beings.

```js
onStart: function(){
	alert('The animation started')
}
```

#### onComplete (function)

A function to be called when the animation is complete.

```js
onComplete: function(){
	alert('The animation is over')
}
```


## License

MIT License
(c) [Antonin Cezard](http://ie.linkedin.com/in/antonin-cezard/)
