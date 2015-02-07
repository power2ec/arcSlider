# arcSlider

No jQuery needed.
<br />

- [Demo](http://plnkr.co/edit/8YuFfEJRMVLeyMKvtcTC?p=preview)

###TODO
Deal with multiple sliders :(

###To use
```sh
// get element
var slider = document.getElementById('arcSlider');

// set options
var options = {
	thickness:50,
	angle:120,
	baseColor:'blue',
	traceColor:'red',
	width:500,
	height:500,
	radius:200
};

// display!!!!!
arcSlider(slider, options);
```

###Options (w/example values)
Note: Credits to jQuery slider, I used their options as a base.

```sh
max: 100
min: 0
value: 0
values: null <-- I believe array of values, hrmmmm
angle:180
radius:100
thickness:5
width:250
height:250
baseColor:"#000000"
traceColor:"#000000"

slide: null <-- function objects, duh
start: null
stop: null
```
