#Grid Layout

A very small and simple CSS grid layout.

##Usage

Simply link to ```grid.css``` in the head of your HTML and add rows and columns within your HTML.

You can use any standard block-level element as a row or column. Rows are denoted by giving the element a class of ```row```.
Columns are denoted by giving the element a class of ```col``` and how wide you want the column, out of 12- twelve being 100% width of the row. 
For example if you want one column to fill a row, set the class name of the column to ```col twelve```.
Each row should contain 12 columns and You can have any assortment of columns within a row, as long as the combined total width of the columns used equals twelve.

I have also included the normalize.css reset before the link to ```grid.css```, as well as including the HTML5 Shiv & Repsond.js JavaScript files. See below.

```html 
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<link rel="stylesheet" href="assets/css/normalize.css">
<link rel="stylesheet" href="assets/css/grid.css">
<!--[if lt IE 9]>
	<script src="assets/js/html5shiv.js"></script>
	<script src="assets/js/respond.js"></script>
<![endif]-->
```

###Example Usage
```html 
<div class="row">
	<div class="col twelve"></div>
</div>
```
```html 
<div class="row">
	<div class="col three"></div>
	<div class="col three"></div>
	<div class="col three"></div>
	<div class="col three"></div>
</div>
```
```html 
<div class="row">
	<div class="col seven"></div>
	<div class="col three"></div>
	<div class="col two"></div>
</div>
```

##Demo
View [the live demo](https://ashmenhennett.github.io/Grid-Layout/) and view the page source for more insight into usage.

##Libraries
- [Normalize](https://github.com/necolas/normalize.css)
- [HTML5 Shiv](https://github.com/aFarkas/html5shiv)
- [Respond](https://github.com/scottjehl/Respond)

##Licensing
MIT License