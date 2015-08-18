# Specificity Rules

* **Rules with more specific selectors have a greater specificity.**

* **ID selectors have a higher specificity than attribute selectors.** <br>`#p123` is more specific than `[id=p123]`

* **Contextual selectors are more specific than a single element selector.**

* **The embedded style sheet is closer to the element to be styled.**

* **The last rule defined overrides any previous, conflicting rules.**

* **A class selector beats any number of element selectors.** <br>`.introduction` beats `html body div div h2 p`

<cite><small>http://www.smashingmagazine.com/2007/07/css-specificity-things-you-should-know/</small></cite>