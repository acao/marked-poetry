marked-poetry
=============

Extends marked.js to provide handy tokens and renderers for free verse poetry

Inspired by [this experiment](https://bitbucket.org/chriskrycho/markdown-poetry) with python-markdown.

It will involve extending the marked lexer to provide a token and block renderer for something like this:

```
\\\
in wilderness I am
		that only melon
		flowering
& splitting
		sending vines out
			everywhere
you are
		in wilderness 
			I am that only
melon flowering
		& splitting
			sending vines out
in the flower world
		out there
			under the dawn
a pale blue cloud
		will be grey water
			at its peak
the mist will reach
		will rain down
			on the flower ground
& shining
		reaching bottom
			where you are
in wilderness
		that only melon flowering
			I am
& splitting
		sending vines out
			everywhere
\\\
```

And it would render properly in html using the marked parser, respecting either spaces and/or indentation and the appropriate line breaks.

Example from [15 Flower World Variations](http://www.ubu.com/ethno/poems/06.html), derived from literal translations of Yaqui Deer Dance Songs, from Ubu Web.

