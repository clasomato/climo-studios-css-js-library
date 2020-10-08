# Climo Studios CSS Library

  

## The #1 small developer library

  

## What is this?

This was made for the Climo Studios group so that we could have a very specific CSS library to work with. As we work with small groups and clients using a huge library was not appealing to us as collective so we are working on our own and thought we would release it to the public as a helpful free tool and so that maybe the other developers out there could help out. Feel free to email me at: jason@climostudios.online

  

### Navgation Guide

```html

<div class="navBarContainer">

<span>

<a href="#">Home</a>

<a href="#">About</a>

<a href="#">Etc</a>

</span>

</div>

```

Simply we make a div and add the class of "navbarContainer". Next we can optionally add a span or just add a tags into the nav the span is there so we can right & center align the nav items.

Editorial: Image/Logo support coming soon.


## Grid Layout
### Example Column layout
The CSS grid was made with simplicity in mind. While 90% of us use flexbox over a CSS grid it is always a nice thing to have so we made a simple but extremely function layout.

To use first you must have a parent div with the class 'row' and then inside that you can place the columns of choice which require the class of 'col' to work then you can add your divisions. We use a 12 column grid 12 being the widest and 1 being the least wide and these are divided into the following categories.

'col': Mobile
'colM': Tablet / Medium screen size
'colL': Desktop / Large device size
```html
<div class="container">
	<div class="row">
		<div class="col col12 colM6 colL4">
			<h1>Example Column 1</h1>
		</div>

		<div class="col col12 colM6 colL4">
			<h1>Example Column 2</h1>
		</div>
	</div>
</div>
```