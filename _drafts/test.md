---
layout: post
title: Testing Jekyll
categories: [technology]
tags: [blog, jekyll]
---

This is just to see how Jekyll works.

Linking to other posts: [Migrating to Jekyll]({{ site.baseurl }}{% post_url  /blog/2019-02-12-migrating-to-jekyll %})
Notice that in page source the source extension is not needed

Linking to pages: [About]({{ site.baseurl }}{% link  about.md %})
Notice that source extension is needed!

Code blocks: 



{% highlight ruby %}
def foo
  puts 'foo'
end
{% endhighlight %}

With line numbers

{% highlight ruby linenos %}
def foo
  puts 'foo'
end
{% endhighlight %}
