# HTML Best Practices

* Always use lowercase tags
* Avoid mismatched closing tags (proper indentation will help)
* Avoid inline styles
* Use a web inspector

```
// Good:

span {
	color: red;
}

<p>
	<span>Hello</span>
</p>

// Bad:

<P><SPAN style="color: red;">Hello</P></SPAN>

```