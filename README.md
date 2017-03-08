# Liquid-SublimeText3-Snippets
A collection of Sublime Text 3 Liquid template snippets to make developing a tad easier.

# Purpose
I love using the Jekyll framework, but find it tedious to type out the liquid templating `{% %}` syntax. So, I made a few snippets for Sublime Text 3 to make life a bit easier. This all started with the `{% comment %}` snippet, and added snippets as I felt necessary. Feel free to use for your projects. 

# Installation
- For OSX users, place each snippet you want to use inside `<user>/Library/Application Support/Sublime Text 3/Packages/User/`
- Windows or other platforms, you're on your own for the location, but there's enough documentation out there.

# Use
The snippet is called by a series of keys followed by `Tab` key. In each snippet file, look for `<tabTrigger>` and you will see the keys needed to initiate the snippet. 

I have not defined the `<scope>` of these snippets. If you would like to do so, here's some more info: [Sublime Text 3 docs](http://docs.sublimetext.info/en/latest/extensibility/snippets.html)

# Make it your own
Don't like the tabtrigger keys, or want to modify the snippet? Go for it.

# Contents
## Comments
`%c` + `Tab` outputs `{% comment %}  {% endcomment %}`

## If
`%if` + `Tab` outputs `{% if %} {% endif %}`  

## Elsif
`%ei` + `Tab` outputs `{% elsif %}`  

## Else
`%e` + `Tab` outputs `{% else %}`  

## For
`%f` + `Tab` outputs `{% for %} {% endfor %}`

## Generic Brackets
`%%` + `Tab` outputs `{%  %}`