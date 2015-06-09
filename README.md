#Quixotic Bootstrap Jekyll

##Intro

Named Quixotic Bootstrap Jekyll because it was built principally using Bootstrap, Jekyll and a bunch of other things (see list of Things), this is a smash-and-grab Jekyll theme much like Poole or Jekyll Bootstrap. The quixotic part comes from wanting to throw in all sorts of funky things, because reasons.

##Things

This repo has things in it, which I didn't write myself but have been formally permitted to use. These things are as follows:

* [Jekyll](http://jekyllrb.com/)
* [Twitter Bootstrap](http://getbootstrap.com/) (v.3.3.4)
* I've gone ahead and used [Noto Sans from Google/Fonts](https://www.google.com/fonts#UsePlace:use/Collection:Noto+Sans)
* ...and so on

##Requirements

If you're running straight offa GitHub Pages, you're grand.

If you're running local, you'll need:
* Probably Git
* Jekyll (plus dependencies)
* Jekyll sitemap
* SASS

##Editorial notes

###Image handling

Kramdown (our default markdown library) provides a way to add classes to images, which is really handy. The default image style is full width or greater, assuming that larger images will be used more and can be treated more uniformly. So if you're adding a large image there's no need to add any extra markdown.

For less-than-full-width images, you'll want to add a style. You can do so with the following syntax:

Syntax|result
-----|-----
`![Picture description](/link/to/picture.jpg){: .image-right }`|Float image to the right (with wrap)
`another syntax`|another result

##Notes & disclosures

- This isn't anywhere near ready.
