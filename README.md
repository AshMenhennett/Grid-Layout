#Grid Layout

A very small and simple CSS grid layout.

##Usage
You can use any standard block-level element as a row or column. Rows are denoted by giving the element a class of ```row```.
Columns are denoted by giving the element a class of ```col``` and how wide you want the column, out of 12- twelve being 100% width of the row. 
For example if you want one column to fill a row, set the class name of the column to ```col twelve```.
Each row should contain 12 columns and You can have any assortment of columns within a row, as long as the combined total width of the columns used equals twelve.

Remember to set the viewport accordingly: ```<meta name="viewport" content="width=device-width, initial-scale=1.0">```.

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
Visit [the live demo](https://ashmenhennett.github.io/Grid-Layout/) and view the source for more insight into usage.

##Libraries
- [Normalize](https://github.com/necolas/normalize.css)
- [Respond](https://github.com/scottjehl/Respond)

##Licensing
MIT License