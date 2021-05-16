+++
title = "Hugo to Zola"
date = 2021-05-16
+++

As anyone who has stubled upon this blog probably knows, hugo has been the
static website generator used for this blog until now. I started using it like
probably most people: Follow the quickstart, find some fancy-looking premade
theme and be happy for a while. I didn't care much for how the theme or even
hugo's (btw. very powerful) templating engine works, the workflow was as simple
as copying one of the other markdown posts to a new filename, delete the actual
content and edit the metadata fields that make the generator happy.

But then the silent desire for some specific feature starts to creep in. That
one post, that should be formatted diffently, this thing you would like to have
a shortcode for, but the theme doesn't provide one.

I don't want to limit myself to any specific topic on this blog. Categories
might come and go and why should they not? The default "post listing" template
for [the template I was using](https://todo) shows all recent posts. This makes
sense, if they are related or at least on the same topic, but I wanted to show
`<h2>` subheadings for the categories, each with the recent posts _of that
category_ under them. 

At this point I forked the theme and implemented it myself glancing over hugos
docs and copy-pasting snippets from stackoverflow until it works. Honestly, yes
it probably was a very hacky solution and the code could have been much simpler.
But I didn't really care. Just work. Just show the posts the way I want to, I'm
here to write them and not to implement hugo themes. 

