---
layout: post
title:  "My Thoughts on Jekyll"
date:   2016-06-20 23:05:05 -0400
categories: jekyll
---

In case you're wondering, I made this site using Jekyll, and did the HTML/CSS without the use of a theme, and it's hosted on Github.

<br>
I just heard about Jekyll last week and it seemed like the perfect technology to build my personal site in. I had a couple options when it came to building this site. One, was to just use vanilla HTML and CSS, which I have done before and made a pretty decent looking site. Another was to go with what I know and build it in Rails or Sinatra. I could've also revisted Wordpress, or used one of the many website-building sites out there like Wix, or Squarespace and used a theme that they provide...but then what good would all the time and money I invested into learning web development be for? But then I found out about Jekyll, and decided to use it.


#### **Why Jekyll?**

Jekyll is a simple, static, blog-aware, static site generator in Ruby.


<br>

##### **It's easy to get started**

Jekyll is a Ruby gem so install all you have to do is:
{% highlight ruby %}
gem install jekyll
jekyll new my-new-site
cd my-new-site
jekyll serve
{% endhighlight %}

With those few commands, you'll have a skeleton for a website with a very basic template that you can customize completely.

<br>

##### **It's versatile.**

When it comes to adding content  you can write the pages in HTML/CSS, Markdown, Textile, or Liquid.

<br>

##### **You can use other Ruby gems**

You can create a gemfile and install other gems. You can even create an asset pipeline using the gem "jekyll-assets"

<br>

##### **You can't be hacked**

Since there's no database, you can't get hacked like you could using Sinatra or Rails

<br>

##### **It's fast**

It only comes with what you need to make a static site, so it won't be slowed down with unnecessary files and features.

<br>

##### **You can use CSS frameworks**

If you love Bootstrap or Foundation, you can use it with Jekyll to make a site just like you would any other way. (I used Materialize CSS). There are also a handful of free Jekyll themes if front-end isn't your thing.

<br>

##### **It's easy to host it for free using Github Pages**

There's a gem, "github-pages" to make it even easier to deploy to Github. You can use a custom URL too.

<br>

##### **It's blog-aware**

Creating a blog is super easy with Jekyll. There's a _posts folder where you can add all your blog posts, and a _layouts folder that has the html template for how you want your posts to display. It's easy to highlight code snippets as well, in case you're a developer that blogs.

<br><br>

#### **Conclusion**

I hope you like the look and feel of my Jekyll site and by now it's probably pretty clear why I chose to use Jekyll.  If you ever need to make a static site, you should really consider Jekyll.