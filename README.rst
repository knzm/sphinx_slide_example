README
====================

::

  $ python virtualenv.py --no-site-packages .
  $ . bin/activate
  (sphinx_slide_example)$ python bootstrap.py 
  (sphinx_slide_example)$ ./bin/buildout 
  (sphinx_slide_example)$ cd doc
  (sphinx_slide_example)$ make pdf

Then open _build/pdf/slide.pdf.
