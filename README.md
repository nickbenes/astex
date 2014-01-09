ASTeX
=====

ASTeX is a system for typesetting professional quality textbooks and journals yourself. It runs under [LaTeX](http://www.latex-project.org/), but also includes shell scripts, vector graphics tweaking, [Mathematica](http://www.wolfram.com/mathematica/) commands and more.

The name (like other TeX packages) is supposed to be a pun and is intended to be pronounced like "Aztec".

ASTeX was originally developed in the '90s by Alex Kasman, then a grad student at [Boston University](math.bu.edu). In addition to handling common typesetting issues, it enabled the integration of vector graphics generated in _Mathematica_ into the publications, and it also dealt really well with things like graphics consistency and color separation, and several popular math books and journals were typeset with it.

In the next few years it will be time for a new edition of one of the books still using ASTeX. _Mathematica_ has gone through several major version changes and has significantly changed how it handles Postscript output, breaking that aspect of the ASTeX stack. The LaTeX and shell script aspects were still pretty solid, but needed a few updates. The authors have been able to find workarounds in the past, but it's time now to either fix the _Mathematica_/Postscript issues or to migrate (with significant headaches) to a new framework.

Now What?
---------
Much of Alex's framework is still good.  I did some work on code updates before a deployment to Aghanistan, and finishing that has been on my back burner since getting back (_i.e._, way too long), and I've learned a lot about development since then. One thing I've learned is that git is really handy for managing source code, and GitHub is the place to be for open source projects. I know I'll have some other people (thanks Paul!) doing some user testing, and there may even be some people out there interested in helping with development. I'm all for bug reports, pull requests, or any other constructive contributions. If you're new to GitHub and want some help figuring out what you can/should do to help, let me know (one way is by going to "Issues" on the right and adding a new one).

What's Here?
------------
I'm putting Alex's original work is in the `original` folder, my unfinished work from 2010 in the `2010` folder, test files in the `test` folder, and everything else in the root directory. I'm keeping track of things that need to be done in `todo.md`, and more general thoughts in `thoughts.md`.

Unless you're running _Mathematica_ from the '90s, this is clearly not yet ready for production, but it's a way to let people access the original ASTeX files, possibly get some ideas for their own projects, and hopefully contribute to this one.
