# KAWS
### NOTE: KAWS is a work in progress at the time of this commit. None of the features used in the README or Wiki are availible yet.
#### A WebSocket client developed for Khan Academy PJS programs. (Please note, this only works in HTML projects. There'll be a tutorial that explains how to port a PJS program to a HTML project.)

# Setting Up
## Adding The Libraires
```html
<head>
	<title>A Really Good Title</title>
	<script src="https://cdn.jsdelivr.net/processing.js/1.4.8/processing.min.js"></script>
	<script src="https://cdn.jsdelivr.net/gh/TehcJS/KAWS@latest/kaws.js"></script>
</head>
```
## Using KAWS.js
```html
<body>
	<script src="https://cdn.jsdelivr.net/processing.js/1.4.8/processing.min.js"></script>
	<script src="https://cdn.jsdelivr.net/gh/TehcJS/KAWS@latest/pjs2html.js"></script>
	<canvas id="canvas"></canvas>
	<script>
		var canvas = document.getElementById("canvas");
		var pjs = new pI(canvas);
		with(pjs) {
			ws.connect("wss://example.com");
		}
	</script>
</body>
```
