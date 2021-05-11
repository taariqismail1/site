---
title: 14. Setting up a personal website for free
subtitle: Using GitHub Pages to host a Jekyll Site
---

## Why do you need a personal website?
Having a personal website might sound like overkill. I thought so too. A friend gave me a copy of Austin Kleon's book, [Show Your Work!](https://austinkleon.com/show-your-work) - it pushed me over the edge in terms of having a personal site. He says:

> _If you get one thing out of this book make it this: Go register a domain name… then buy some web hosting and build a site_

A personal site is where people can find you, and where you can share your ideas with the world. Getting comments from other people improves your ideas significantly.

## How to do it?
In addition to some content, you need a few things to get your site up and running:

1. A domain (e.g. www.yourname.com)
2. A website and somewhere for the it to live (hosting)

### Domain
You can buy a domain name for around £10 a year - unfortunately there’s no way of avoiding this, unless you’re happy with something like taariq.squarespace.com. Have a look on [GoDaddy](https://uk.godaddy.com) or search 'domain name' on Google.

### Website and hosting
Here are some broad options (not exhaustive):
1. __Website builders__ - Many sites (e.g. [GoDaddy](https://uk.godaddy.com), [SquareSpace](https://squarespace.com) that sell domains will offer a website builder too. It's low hassle - all you have to do is sign in and start building your website using pre-defined templates. Cost: £10 - £15 per month
2. __Custom website builders__ - e.g. [Webflow](https://webflow.com), [Ghost](https://ghost.org). These are similar to the plain website builders, but offer a lot more customisation and flexibility, such as monetising newsletter subscribers. You can pick a theme and then customise it. Cost: £8 - £10 per month
3. __Static site hosted on [GitHub Pages](https://pages.github.com)__. [GitHub](https://github.com) is a code hosting platform for version control and collaboration. It lets you work with other people on projects. GitHub Pages allows you to host a website for free. Cost - £0 per month

There are many options when building a static site. __I decided to go with [Jekyll](https://jekyllrb.com)__. There are lots of other options - you can build the site from scratch using HTML and CSS, or you can use Mobirise to build your site (in the same way you would on SquareSpace) and then export the site as raw files. In any case, you can still host it on GitHub Pages.

## Getting started with Jekyll and GitHub
I decided to use Jekyll as it has an inbuilt blogging engine. You can choose a theme at [JekyllThemes](https://jekyllthemes.io) and copy it into your GitHub repository (or you choose one of a few themes from within GitHub - have a look at the GitHub Pages site for more details). You can then set up your site and [connect your domain](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site).

The last thing you’ll need on your site is some content. You enter this by editing the website files. Jekyll uses [Markdown](https://www.markdownguide.org/cheat-sheet), which changes plain text to formatted text. It’s very intuitive, and when you’re typing into the editor you can almost see what the final result will be. 


## GitHub Pages - is it really free?
I decided to go with GitHub Pages for a few reasons - __I wanted to learn about GitHub and version control__, and of course, it’s free.

There is a bit of setup time, but after that it doesn’t take up too much time to maintain and upload posts (once you’re familiar with Markdown). It also gives you the usual things like analytics though Google Analytics.

__Working with GitHub won't give you a beautiful user interface__. You have to be comfortable with text, but it does offer a lot of flexibility - e.g. you can just make a page with a completely different theme and host it on the site.

## What are the downsides?
There are clearly lots of positives, so what are the downsides? There's a size limit and a bandwidth limit - given it will be a website of mainly text, these limits aren't of much concern when starting out.

Here are some of the issues I came across:

1. __It takes a little while to figure things out__. The BeautifullJekyll theme I'm using says you can be up and running in 5 minutes. That's probably true if you've done it before, but it took me slightly longer.
2. __You'll have to write all your posts in markdown and formatting non-text elements can be fiddly__. For example, to resize an image you have to specify its height, rather than dragging to resize (as you do in Substack). Writing in Markdown is quite easy once you understand the sytnax. This takes about 5 minutes to learn (this time it is 5 minutes).
3. The __other disadvantages__ I could find on the internet include it being a static website, you'll have to make some effort for SEO and the lack of technical support. My counters to these are:
- You'll probably have a static website anyway
- Once you've installed a plugin, you're good to go. Just add your descriptions at the top of each page
- You'll be able to find most of what you're looking for on the internet - stackoverflow.com

__There might be other issues I haven’t yet come across. As part of me learning in public, I’d like to get ideas from people why this isn't a very good idea.__

## Conclusion
GitHub pages is a very easy way of getting a site set up, whilst trying things out. If you want to learn some new skills then it’s something you should do vs the other options. If you want to just get a site up in a few minutes and aren’t too interested in the technical side, it’s worth paying for the other options.

I’ve enjoyed using it and learning, so will likely continue for the short term and evaluate options again later.

Although this hasn't been a step-by-step manual on how to set up a website for free, I've tried to include enough links along the way for you to follow them through.
