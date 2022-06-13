# cparse

A simple parser for C that looks for brace brackets and skips everything else.

As an example, the formatter inserts printfs after every opening brace and before every closing brace.  This example doesn't do much, but might give ideas on how to easily instrument code.  The code does not need to be C, it only needs to consist of bracketed text, like most programming languages. 

The brackets don't need to be actual bracket characters, like `{ ... }` and `( ... )` and `[ ... ]` and `< ... >`.  The brackets can be keywords like `if ... end if`.

Python and markdown rely on indentation and don't fall into the category of bracketed text.  If you want to instrument Python code or grok markdown, you will need a slightly different parsing strategy (probably only a few lines long, too).

To use, load insert.html into a browser and press the "insert" button.
