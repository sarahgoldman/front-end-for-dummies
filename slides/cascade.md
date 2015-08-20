# The Cascade

Rules are applied according to their importance:<br><br>

<table>
	<tr><th></th><th>Origin</th><th></th><th>Importance</th></tr>
	<tr><td>1</td><td>user agent</td><td>(browser)</td><td>normal</td></tr>
	<tr><td>2</td><td>user agent</td><td></td><td>!important</td></tr>
	<tr><td>3</td><td>user</td><td>(user preferences)</td><td>normal</td></tr>
	<tr><td>4</td><td>author</td><td>(style sheet)</td><td>normal</td></tr>
	<tr><td>5</td><td>CSS Animations</td><td></td><td></td></tr>
	<tr><td>6</td><td>author</td><td></td><td>!important</td></tr>
	<tr><td>7</td><td>user</td><td></td><td>!important</td></tr>
</table>
<br>

In the case of equality, the **more specific rule will take precedence**...


<cite><small>https://developer.mozilla.org/en-US/docs/Web/CSS/Cascade</small></cite>