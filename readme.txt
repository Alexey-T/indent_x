Indent_x is a forgiving indentation library.

It uses regular expressions (probably more than it should) to identify tokens to:

* insert new lines
* increase indentation (begin tag/object)
* decrease indentation (end tag/object)

This technique has the following benefits:

* doesn't require valid strict XML or JSON (close enough should be good enough)
* preserves attribute order
