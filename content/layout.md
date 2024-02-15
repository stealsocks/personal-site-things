---
title: Layout
---

This is the highest-level decision you can make.

Most other design details will follow from this one. Like fonts: if you go with a modern bento-box style, you're probably going to use a geometric sans-serif. If you want your site to look like a beautifully typeset book, you better find a great serif.

Most of the patterns here are meant to be used for the **home page** of your site. Content pages are generally simpler because they have to work for every essay/post, the home page is under your direct control and allows for cooler designs.

I'm going to skip past the simple single-column vertical scroll page, because it's the web default (and it's a pretty good default too!).

## Vertical split

<figure>
	<a href="https://andymatuschak.org/">
		<img src="/photos/andy.png"> 
		<figcaption>Andy Matuschak</figcaption>
	</a>
</figure>

Simple enough (thought surprisingly difficult to implement), it's a step towards a more dense layout. It doesn't work great on phones, because the columns are usually set to wrap under the previous one in one long column, which is the same thing as having a single column page to start off with.

*But who cares about phones?* 

Sure, more than half your visitors are going to be on mobile devices. But that shouldn't keep you trapped within the forced minimalism of "modern" layouts.

---

## Horizontal scroll


<figure>
	<a href="https://alexanderobenauer.com">
		<img src="/photos/horizontal-scroll.png"> 
		<figcaption>Alexander Obenauer</figcaption>
	</a>
</figure>

If you really want to max out the information density of a page, you can't do much better than a vertical page + horizontal-scrolling sections. 

It is the classic *"browse, and go deeper when you feel like it"* layout.

You can fit in a ton of content like this – the "blog" section could contain the entire history of your writing (not that much, since you never seem to get around to publishing) without wasting vertical space.

**Warning!** This layout often sucks for people who aren't using a trackpad or smartphone. You'll need to add some kind of Javascript-based affordance for them to scroll (clickable arrows, maybe) or inform them that `shift` + scroll is what they need to try.

---

## Horizontal split

This one is surprisingly uncommon, compared to how well it can work for certain types of content (portfolios, multiple sections of writing). 

<figure class=left>
	<a href="https://gemmacope.land/">
		<img src="/photos/copeland.png"> 
		<figcaption>Gemma Copeland</figcaption>
	</a>
</figure>

It's not very different from a sidebar. Just like the sidebar, it contains the [navigation](/navigation) for your site. But it's size means that it can hold way more information. 

---

## Table / grid

<figure>
	<a href="https://gemmacope.land/">
		<img src="/photos/copeland.png"> 
		<figcaption>Add Chia's site</figcaption>
	</a>
</figure>

Tables on the web are...tricky. It's really nice that there's a defined `<table>` tag, but there's also the fact that styling them sometimes isn't as easy as using a bunch of `<div>` elements with flex/grid. 

The best place to use this layout is for comprehensive indexes, the kind that lay out your whole existence in one, super-dense grid of text. 

But you can also bring it in more subtly (like [Paco's site](add archive link) does), depending on your whitespace preferences. 

<figure class=left>
	<a href="https://gemmacope.land/">
		<img src="/photos/copeland.png"> 
		<figcaption>Add the grid site</figcaption>
	</a>
</figure>

Make sure they work okay on mobile though, you can choose between making them wrap (for grid/flexbox) or scroll horizontally (proper tables). 

For styling, you can play around with border styles, cell colors and padding, fonts, and column-widths. For peak density, try a grid of grids; tables nested within a multi-column layout.


---

## Bento

In most cases, the layout for each bento-style page needs to be tailored to it's contents. 

---

## App

Overkill? Maybe. 

https://brianlovin.com/writing/

## Timeline

<figure>
	<a href="https://gemmacope.land/">
		<img src="/photos/copeland.png"> 
		<figcaption>Add Colly</figcaption>
	</a>
</figure>

Implementation is an open problem, but the idea of your home page being a timeline of your life will directly affect it's layout, so I'm counting it as one. 

A simple vertical list is on the easier side of the scale (and can look pretty good). 

Simon's site is on the other end, and I'm slightly afraid to find out how he does it.

---

## Two/three-column

This is "just" a vertical page, yes. But hardly anybody does multiple columns of text on the web anymore! It's a shame, beause `column-count: 2` makes it so easy.

