---
layout: post
title:  "Building this site"
date:   2015-07-26 18:05:00
categories: 
---
I spent a long time deciding between using GitHub/Jekyll or WordPress for my blog.
The former is fast, customizable, and gives hacker-cred, while the latter is easy to set up and offers non-static site features.
As you can see: I ended up going with the GitHub/Jekyll combo.
This first post will serve as a record of my experiences building this blog without WordPress magic.
Because I want the blog to be focused on less-front-end-type things, there will be no follow-ups to this post.
As I build the blog, the updates will appear here.

I want to establish I'm not some elite hacker web developer.
The folks that make the amazing tools deserve all the credit.
I'm basically just figuring out how to use them and giving more praise.

### MathJax

$$\LaTeX$$ is beautiful.
It's probably half the reason I got into math and CS theory.
I use LaTeX everywhere I can.
I even had a double-space document class for my undergraduate liberal arts classes.
There's no way I could bear to have a blog (which I intend to be technical) without LaTeX.

[MathJax](http://www.mathjax.org/) is incredible.
It makes me almost amazed at the power of JavaScript.
Installing LaTeX normally takes a hefty amount of time due to all the packages, libraries, etc.
Somehow the MathJax team managed to condense a substantial portion into one script:

~~~
<script src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML"></script>
~~~

In my initial research online I saw a lot of warnings about difficulties with working MathJax into Markdown syntax.
Luckily (praise) the Kramdown engine in Jekyll makes everything easy.
In-line math is as simple as `$$x_1 \lt x_2 \leq x_3$$`, which produces $$x_1 \lt x_2 \leq x_3$$.
Display math involves simply putting the double dollar signs on their own line.
The following code

~~~
$$
x_1 \lt x_2 \leq x_3
$$
~~~

results in

$$
x_1 \lt x_2 \leq x_3
$$

