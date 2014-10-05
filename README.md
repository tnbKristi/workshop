Programming Workshop
========

A website dedicated to collecting exercises to improve your HTML, CSS, or JavaScript skills. Used in Girl Develop It Philly's Pair Programming Workshop.

How to Contribute
==================

We need more exercises! It's easy to contribute.

This site is built using [Octopress](http://octopress.org/) - a markdown-based blogging platform. All of the exercises are created as a blog post using the `markdown` syntax.

### [An Example Post](https://raw.githubusercontent.com/tnbKristi/workshop/master/source/_posts/2014-09-22-html-basics.markdown)

## Creating a new Post

- First, fork this repository.
- Install the dependencies for the blog:  
```
gem install bundler
rbenv rehash    # If you use rbenv, rehash to be able to run the bundle command
bundle install
```

- Then, create a new post: `rake new_post["My Post Name"]

Check out the docs on Octopress to see what options you have in the post.


## Post Header Settings

There's a few things your post will need to work on this site:

```
---
layout: post
title: "HTML Basics"
date: 2014-09-22 16:39:16 -0400
summary: "An intro to basic HTML elements, including tables, and forms."
comments: true
categories: ["HTML & CSS"]
---
```

**layout, date, comments** These should all be generated by default for you.

**title** This should also be generated for you.

**summary** Required. Will display in the category list to give students an idea of your exercise.

**categories** Required. Without this, it will not display in the exercise category lists!

_Available categories:_
- "HTML & CSS"
- "Advanced CSS"
- "Beginner JS"
- "Advanced JS"

Important! The categories must be in the same case above to match up.

Once you've created your post and it's ready to go, submit a pull request and we'll review. Thanks for contributing!