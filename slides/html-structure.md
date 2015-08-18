# HTML Structure

Just like XML, most HTML tags require a corresponding closing tag.

```
<html>
	<head>
	</head>
	<body>
		<div>
			<p>Example</p>
		</div>
	</body>
</html>
```

However, the HTML tags that do not require a closing tag are called **void elements**. Unlike XML, they are not self-closing and do not require a slash at the end.

```
<img src="photo.jpg" alt="Photo">

<hr>

<input type="text" name="photoTitle">
```