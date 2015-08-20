# Selectors

<table class="full-width">
	<tr>
		<th>CSS</th>
		<th>HTML</th>
	</tr>
	<tr>
		<td>
			<pre><code>
// Selector
p { 
	padding: 10px; 
}

// Class selector
.example { 
	background: orange;
}

// ID selector
#intro { 
	font-style: italic;
}

// Contextual selector
p span { 
	color: green; 
}
			</code></pre>
		</td>
		<td>
			<pre><code>
<div id="intro">Hello <span>World</span></div>
<div class="example">
	<p>I'm a <span>padded</span> paragraph</p>
</div>
			</code></pre>
		</td>
	</tr>
</table>

<div class="css-example">
	<div id="intro">Hello <span>World</span></div>
	<div class="example">
		<p>I'm a <span>padded</span> paragraph</p>
	</div>
</div>