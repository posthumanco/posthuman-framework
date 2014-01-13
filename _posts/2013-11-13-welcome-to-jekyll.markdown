---
layout: post
title:  "DOCS"
date:   2013-11-13 10:31:44
categories: docs documentation
banner: http://www.fillmurray.com/g/2000/400
---

##Grid System

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
			<div class="small-12 medium-3 large-3 columns">
				3 columns
			</div>
			<div class="small-12 medium-3 large-3 columns">
				3 columns
			</div>
			<div class="small-12 medium-3 large-3 columns">
				3 columns
			</div>
			<div class="small-12 medium-3 large-3 columns">
				3 columns
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