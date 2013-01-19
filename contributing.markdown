---
layout: post
title: Contributing
category: Coding
tags: jQuery
year: 2013
month: 01
day: 01
published: true
summary: Contributing
---

365 Days of jQuery uses GitHub, Jekyll and Markdown.

If you don't already have a GitHub account, you can set one up and find out more information here: <https://github.com/>

Once you have a GitHub account, there's a few ways you can help contribute.


## Super Simple Way

<object width="420" height="315"><param name="movie" value="http://www.youtube.com/v/atMzOPmPwOA?version=3&amp;hl=en_US&amp;rel=0"></param><param name="allowFullScreen" value="true"></param><param name="allowscriptaccess" value="always"></param><embed src="http://www.youtube.com/v/atMzOPmPwOA?version=3&amp;hl=en_US&amp;rel=0" type="application/x-shockwave-flash" width="420" height="315" allowscriptaccess="always" allowfullscreen="true"></embed></object>

### GitHub

Login to your GitHub account, then go to: <https://github.com/365daysofjquery/365daysofjquery.github.com>

Here you'll see all the files being used. Simply click on the file you'd like to edit, then click edit.
Make the changes, add a commit note, send a pull request. Done!


## Super Duper Awesome Way

This way will require a bit of a learning curve if you're not familiar with Jekyll or Markdown, but it's well worth it.


### Jekyll

[Jekyll](http://jekyllrb.com/) is the engine behind GitHub Pages, it takes a template directory and converts this to a static website.


### Markdown

Again used by GitHub, [Markdown](http://daringfireball.net/projects/markdown/) is a great way to write quick, efficient, maintainable code. Writing in plain text, Markdown will then be converted to HTML.


### Working Locally

Using Jekyll it's possible to start up a local Jekyll server and work locally on your machine.
This means that you can add new posts, change styles and do anything you like to the site and test things out.

Once you've made your updates, previewed the site locally and happy with everything you've done, you can then commit the code and send over a pull request with all the awesome work you've done.


### Setup

To get started, first clone the repository (otherwise known as 'repo').
To do this open up Terminal, then you're going to want to change directory `cd` to where you'd like the repo to be on your computer, then clone the repo:

	git clone https://github.com/365daysofjquery/365daysofjquery.github.com.git


This will take all the files and add them to your chosen directory in a folder called `365daysofjquery`, `cd` into that directory:

	cd 365daysofjquery


Next, if you're on a mac, you should already have Ruby installed, make sure you're running the latest version. Depending on your administration settings, you might need to type `sudo` before the commands, for convenience I've added them in.

	sudo gem update --system


Then you need to install Jekyll.

	sudo gem install jekyll


You'll also need [RDiscount](https://github.com/rtomayko/rdiscount) to convert the Markdown, install this.

	sudo gem install rdiscount


When you've installed those, you should then be able to start up a Jekyll server and view the site locally at `localhost:4000`.

	sudo jekyll --server


If you're new to all this Terminal business and got this up and running first time, congratulations!

If you're stuck or encountered any bug messages or unable to get it working, please create an issue and I'll try and help out. Took me a few attempts initially, but since getting it working the first time I haven't had any problems.

Good Luck!