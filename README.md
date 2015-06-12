#Quixotic Bootstrap Jekyll

##Intro

Named Quixotic Bootstrap Jekyll because it was built principally using Bootstrap, Jekyll and a bunch of other things (see list of [Things](#things)), this is a smash-and-grab Jekyll theme much like Poole or Jekyll Bootstrap. The Quixotic part comes from wanting to throw in all sorts of funky things, because reasons.

Give me a shoutout to [@robsafar on Twitter](http://twitter.com/robsafar) if you like.

##Things

This repo has things in it, which I didn't write myself but we're licensed to use. These things are as follows:

* [Twitter Bootstrap](http://getbootstrap.com/) (v.3.3.4)
* The homepage scrolling script is [OnePageScroll](https://github.com/peachananr/purejs-onepage-scroll) by [Pete R.](https://github.com/peachananr)

Not in the repo itself but referenced (and are therefore dependencies) are:

* [Open Sans and Open Sans Condensed via Google/Fonts](https://www.google.com/fonts#UsePlace:use/Collection:Open+Sans+Condensed:700|Open+Sans:400,700)
* [Glyphicons](http://glyphicons.com/) (via Twitter Bootstrap)
* ...and so on

##Requirements

If you're running straight offa GitHub Pages, you're grand. QBJ will work out-of-the-repo (making sure to title your branch `gh-pages`).

If you're running local or server, you'll need:
* Possibly Git
* Jekyll (plus dependencies)
* Jekyll sitemap
* SASS

##Editorial notes

###YAML

YAML|Effect
-----|-----
image:|the post heading image (displays on homepage)
subtitle:|subtitle appears directly after the title
teaser:|shows in previews, else gives the first 50chars of your content
glyph:|[Glyphicons](http://getbootstrap.com/components/#glyphicons) used for pages in the menu

###Citations

Footnotes are handled the normal way (will explain more soon).

Blockquote citations... let me get back to you. I need to work out a method that doesn't involve plugins (forbidden in GitHub Pages).

###Homepage feed

Currently limits to 3 most recent posts, displayed in a one-page-scrolling format. This scrolling script deactivates when the browser width is 600px or less, so on lower-spec mobiles it should smooth-scroll.

Note that the homepage is not designed to be print-friendly. At all. Better get some A4 mahogany frames for those other pages though, they're pretty mind-blowing. 

###Image handling

We're doing full-width-or-greater images, and the best way to implement this involves an editorial adjustment. If you have an image you want to make a big deal out of, you'll want to use markup rather than markdown, as follows:

    <figure><img src="http://link.address" alt="Don't forget the alt text"></figure>

I'm working on a snippet of cheeky JS to repurpose the `alt` text as a caption for any image in the main body (I'm thinking about it anyway).

##Notes & disclosures

- This is a total work in progress. My process for my own site currently involves testing and pushing on this, then testing and pushing on my site.
- As far as possible, I'm trying to leave borrowed code completely intact. That way if the original source disappears (see links in the [Things](#things) section) anyone can pull them straight out of this repo in their original form.
