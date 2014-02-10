Evan Borgstrom's CV
===================

I use TeXLive via MacPorts::

    sudo port install texlive texlive-fonts-extra texlive-latex-extra

Then you can use ``pdflatex`` to compile::

    pdflatex eab-cv.tex

The ``eab-cv.cls`` was adapted from harnon-cv.cls_. I changed the nomenclature
of some of the commands since I didn't like specifying ``\youremail{}`` when
the CV is obviously about me in the first place. I also changed the fonts, some
of the margins, added better hyperlink support and a bunch of other small
tweaks. Like the original my ``.cls`` file is released into the public domain,
feel free to use it for your own CV.

.. _harnon-cv.cls: http://www.ctan.org/tex-archive/macros/latex/contrib/harnon-cv
