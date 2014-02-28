---
layout: post
title: Using the Markdown in Developer Marketing Campaigns 
subtitle: A Marketer's Experience with the Popular Markup Language
date: 2014-02-27
comments: false
author: Craig Oda
tags:
  - marketing tools
excerpt: Markdown is a popular formatting language often used by developers for documentation or to communicate with each other.  Marketers need to learn it too.

---

![StackEdit Online Markdown Editor](/img/blog/2014/02/2014-02-27-stackedit.png "StackEdit"){:.pull-right .img-responsive}

![mdcharm.png](/img/blog/2014/02/mdcharm.png "MdCharm Markup Editor")

[Markdown](http://en.wikipedia.org/wiki/Markdown "Markdown Wikipedia Entry") is a popular formatting language often used by developers for documentation or to communicate with each other.  It is often used in readme files, blogs, forums, and question and answer sites.

{{ excerpt_separator}}

GitHub, reddit, Diaspora, [Stack Overflow](http://stackoverflow.com/ "Stack Overflow"), and SourceForge use Markdown.  It is also the common format for documentation engines or static web site generators such as [Jekyll](http://jekyllrb.com/ "Jekyll").  

To quickly and cheaply publish useful information to developers, marketers will need to deal with Markdown at some point.  There are many ways to avoid using Markdown, but it seems a good skill to have.  

For example, one of the really common uses for Markdown is to include a snippet of code into the email, forum post, blog post, response on a QA site, or short piece of documentation.  This may not be a problem for the older generation of marketers that are not putting code snippets into their marketing material, but there's a new crop of marketers, often from product marketing, that are engaging with the community of developers.  This often entails sending some level of short configuration or code snippets to people. 

I was drawn into the Markdown editing world by:

![GitHub.png](/img/blog/2014/02/GitHub.png "GitHub Cats")
![StackOverflow.png](/img/blog/2014/02/StackOverflow.png "Stack Overflow Answers")
![Discourse.png](/img/blog/2014/02/Discourse.png "Discourse")
![jekyll.png](/img/blog/2014/02/jekyll.png "Jekyll")
![octopress.png](/img/blog/2014/02/octopress.png "Octopress")


Kunalo recently moved our blog over to Jekyll and I'm writing this blog post in Markdown using a graphic editor called [MdCharm](http://www.mdcharm.com/ "MdCharm main site").  It's not quite as easy as writing a press release in MS Word, but it's easier for me than using a text editor like Emacs.

Images are a bit tricky as I haven't figured out how to get them to display properly in the editor.

![mdcharm_screenshot.png](/img/blog/2014/02/mdcharm_screenshot.png " MdCharm Screenshot")

The images looks fine in a web browser and can be tested on the same computer with Jekyll using 
```$
jekyll --server --auto
```

You can then preview the blog post run through Jekyll at: 
```
http://localhost:4000
```

Mashable compiled a great list of Markdown editors called [78 Tools for Writing and Previewing Markdown](http://mashable.com/2013/06/24/markdown-tools/ "Mashable article on Markdown tools").


There were a number of online editors including:

* Dillinger
* StackEdit
* Mou

A friend of mine also recommended [MultiMarkdown for Mac](http://multimarkdown.com/ "MultiMarkdown editor for Mac")

People on the Ubuntu Discourse forum pointed me to [Sublime Text](http://www.sublimetext.com/ "main sublime site") and [Light Table](http://www.lighttable.com/ "Light Table editor").  Although these look great, I wasn't able to get Light Table to work properly and Sublime is a bit pricey for me.  

For now, MdCharm does the job.

Here's an example of an email I sent to a developer about our corporate blog.  I'm trying to figure out how to get help changing the look of our blog so that it has better formatting of excerpts.  In most companies, managing the blog is the responsibility of marketing.  So, this is applicable to a wide range of marketers.  I'm using Gmail, Google enterprise apps to send the email is Firefox. 

In the first picture, I just copied and pasted a configuration snippet into the body of the email.

![markdown_raw.png](/img/blog/2014/02/markdown_raw.png "Raw markdown before sending")

Using the browser plug-in, [Markdown Here](http://markdown-here.com/ "Markdown Here") I simply right-click and select Markdown Toggle, making the configuration snippet and marketing question easier to understand.

![markdown_rendered.png](/img/blog/2014/02/markdown_rendered.png "Markdown format rendered with Markdown Here")

The Markdown Here site has several other [great examples](http://markdown-here.com/features.html "great examples of markdown use"). 

<hr>


 

 
