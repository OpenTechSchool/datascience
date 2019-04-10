# Data Science

![](data_not_data.jpg)

## What can I find here?

This repo contains OpenTechSchool's data science [website](https://opentechschool.github.io/datascience/), plus (eventually) materials for tutorials, workshops, etc. related to data science.

## Can I contribute?

Yes please! Contributions of any kind are welcome.

## What's Hugo?

Hugo is a super fast static website generator based on [Go](https://golang.org/).
Pick a [theme](https://themes.gohugo.io/), tweak it a bit, add some content, build and deploy. It's that easy. There are lots of SWGs to choose from, but Hugo offers
the benefits of being blazing fast and comparatively easy to use. For R users
there's also the added benfit of Rstudio integration via the [blogdown](https://bookdown.org/yihui/blogdown/) package.

The best way to learn about Hugo is by reading it's [documentation](https://gohugo.io/documentation/).

#### Hugo "Learn" Theme

The Hugo "Learn" theme is made for documentation, online courses, etc. It has
a nice, simple layout, syntax highlighting, and it offers the ability to construct
sidebar menus of any depth. The best way to learn the ins and outs of this theme
is to check out it's [documentation](https://themes.gohugo.io/theme/hugo-theme-learn/en).

## What's Markdown?

Straight from the horse's mouth:

> Markdown is a text-to-HTML conversion tool for web writers. Markdown allows you to write using an easy-to-read, easy-to-write plain text format, then convert it to structurally valid XHTML (or HTML). - [*Daring Fireball*](https://daringfireball.net/projects/markdown/)

Never used Markdown? Get started with this [guide](https://www.markdownguide.org/basic-syntax).

One frequent issue is figuring out how to view markdown locally. A good,
simple and, best of all, free option is the [Atom](https://atom.io/) text editor
with the [Markdown Preview](https://atom.io/packages/markdown-preview) add-on.

## What about Jupyter Notebooks and R Markdown?

Much data science is done using Jupyter Notebooks or R Markdown. Both these
instances of [literate programming](https://en.wikipedia.org/wiki/Literate_programming)
can be easily converted into either Markdown or HTML.

*(Note from Gershom: I'm still working out the optimal way to do this. It's probably best to create new post with Hugo, 
convert .ipynb/.rmd to .md, transfer the YAML/TOML header, then replace original post.)*
