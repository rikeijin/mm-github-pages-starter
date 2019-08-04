---
title: "Welcome to Jekyll!"
date: 2019-04-18T15:34:30-04:00
categories:
  - blog
tags:
  - Jekyll
  - update
---

You'll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

```ruby
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
```

{% highlight ruby linenos%}
def foo
  puts 'foo'
end
{% endhighlight %}

$\Gamma(x)$

{% highlight html %}
{% raw  %}
{% if page.mathjax %}
  <script type="text/x-mathjax-config">
   MathJax.Hub.Config({
       extensions: ["tex2jax.js"],
       jax: ["input/TeX", "output/HTML-CSS"],
       tex2jax: {
           inlineMath: [ ['$','$'], ["\\(","\\)"] ],
           displayMath: [ ['$$','$$'], ["\\[","\\]"], ["\[","\]"] ],
           processEscapes: true
       },
       "HTML-CSS": { availableFonts: ["TeX"] }
   });
  </script>
  <script type="text/javascript" async
	        src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.5/latest.js?config=TeX-MML-AM_CHTML">
  </script>
{% endif %}
{% endraw %}
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
