---
layout: post
title:  "Hello world"
date:   2015-09-09 15:35:52
categories: work data
---

This is a new webpage or blog post.

Jekyll also offers powerful support for code snippets:

{% highlight python %}
"""
XML file parser, based on Alains input
"""

from xml.dom.minidom import parse

xml = parse('ESS11.xml')
print xml.childNodes

sample = xml.firstChild
print sample.childNodes

poi = sample.childNodes[2]
print poi.childNodes

scan = poi.childNodes[2]
print scan.childNodes

scanparameters = scan.childNodes[4]
print scanparameters.childNodes

for i in scanparameters.childNodes:
    print i.toxml()
{% endhighlight %}
