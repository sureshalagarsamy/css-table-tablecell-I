# Equal height for adjacent columns

Basic useful feature list:

 * This works in all versions of Firefox, Chrome and Safari, Opera from at least version 8, and in IE from version 8.
 * There are many methods to do the same. But this is the easiet way i felt. 
 * At the end our goal is HTML/CSS: Making two floating divs the same height.



To work on this you need simple HTML and CSS file. enough :)

```html
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Equal column heights</title>
<link rel="stylesheet" type="text/css" href="style.css">
</head>

<body>
	<div class="main">
		<div class="first-column">
			A<br/>
			B<br/>
			C<br/>
			D<br/>
			E<br/>
			F<br/>
			G<br/>
		</div>
		<div class="second-column">
			Some content!
		</div>
	</div>
</body>
</html>
```

```css
.main {
  display:table-row;
  font-family:verdana;
  font-size:12px;
  padding:2px;
}

.first-column {
  width:90px;
  display:table-cell;
  background-color:#DDD;
  border:1px solid #000;
}

.second-column {
  width: 180px;
  display: table-cell;
  background-color: #F2F2F2;
  border:1px solid red;
}
```

### OUTPUT
![ScreenShot](https://cloud.githubusercontent.com/assets/6780840/26531063/fd35556a-43fe-11e7-8508-08865553d4bc.png)
