---
layout: post
title:  "DOCS"
date:   2013-11-13 10:31:44
categories: docs documentation
---

###Grid System

<p>
	<div class="demo">
		<div class="row">
			<div class="small-12 medium-12 large-12 columns">
				12 columns
			</div>
		</div>
		<div class="row">
			<div class="small-12 medium-6 large-6 columns">
				6 columns
			</div>
			<div class="small-12 medium-6 large-6 columns">
				6 columns
			</div>
		</div>
		<div class="row">
			<div class="small-12 medium-4 large-4 columns">
				4 columns
			</div>
			<div class="small-12 medium-4 large-4 columns">
				4 columns
			</div>
			<div class="small-12 medium-4 large-4 columns">
				4 columns
			</div>
		</div>
	</div>
</p>

<p>There are 3 media queries by default: <code>.small-#</code>, <code>.medium-#</code>, <code>.large-#</code> along with the <code>.column</code> or <code>.columns</code> classes. You define the number of columns you would like the div 

<p>
{% highlight html %}
<div class="row">
	<div class="small-12 medium-8 large-6 columns">
		<p>Aliquam eget tempus risus. Morbi consequat turpis eu augue pellentesque bibendum.</p>
	</div>
</div>
{% endhighlight %}
</p>

###Buttons

#####Button colors

<button class="primary small">.primary</button>
<button class="secondary small">.secondary</button>
<button class="alert small">.alert</button>
<button class="disabled small">.disabled</button>

#####Button Sizes

<button class="primary tiny">.tiny</button>
<button class="primary small">.tiny</button>
<button class="primary">default</button>
<button class="primary large">.large</button>
<p><button class="primary expand large">.expand</button></p>

###Headers

#h1. Header

##h2. Header

###h3. Header

####h4. Header

#####h5. Header

######h6. Header

###Blockquotes

> Suspendisse potenti. Aliquam dictum, diam sit amet mollis laoreet, metus urna ultricies neque, a tincidunt velit lorem eget justo. Curabitur non metus tempor, euismod lorem condimentum, suscipit quam. Vestibulum blandit massa sed euismod ultrices. Phasellus felis metus, sodales vitae odio eget, consectetur convallis lacus. Integer congue lorem sem, ac porttitor nibh elementum a. Donec ut justo dictum, auctor odio ac, cursus nunc. Vestibulum vel ante risus. Quisque erat tellus, dignissim a placerat at, rhoncus vitae nulla. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Quisque interdum risus in arcu placerat, eget consequat libero venenatis. Proin nec eleifend ligula. <cite>Nobody Important</cite>