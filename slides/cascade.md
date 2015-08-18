# The Cascade

1. It first **filters all the rules** from the different sources to keep only the rules that apply to a given element. 
2. Then it **sorts these rules according to their importance**, that is, whether or not they are followed by `!important`, and by their origin. 
3. In case of equality, the **more specific rule will take precedence**.

<table>
	<tr><th></th><th>Origin</th><th>Importance</th></tr>
	<tr><td>1</td><td>user agent</td><td>normal</td></tr>
	<tr><td>2</td><td>user agent</td><td>!important</td></tr>
	<tr><td>3</td><td>user</td><td>normal</td></tr>
	<tr><td>4</td><td>author</td><td>normal</td></tr>
	<tr><td>5</td><td>CSS Animations</td><td></td></tr>
	<tr><td>6</td><td>author</td><td>!important</td></tr>
	<tr><td>7</td><td>user</td><td>!important</td></tr>
</table>

<cite><small>https://developer.mozilla.org/en-US/docs/Web/CSS/Cascade</small></cite>