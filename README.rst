.. contents::

Introduction
============
Transforms HTML to CNXML.


Needed libraries
================
Some python libraries are needed:
tidylib - http://pypi.python.org/pypi/pytidylib/0.2.1
readability-lxml - http://pypi.python.org/pypi/readability-lxml/0.2.3


How to run
==========
python testbed_html.py
  -or-
python testbed_html.py -noval


Contents of folders
===================

Folders for all transformations
    jing                  Jing Relax NG validator and validation files.
    www                   XSLT transformation files.
    www/catalog_xhtml     XHTML Entity Catalog files.

Folders for HTML transformation
    testbed_html          HTML testbed. Contains a set of HTML which should be converted.
    testbed_html_output   CNXML output of the HTML testbed.

Files for HTML transformation
    htmlsoup2cnxml.py     Transformation HTML (String) to CNXML (String).
                          This file is a slightly modified version of htmlsoup2cnxml.py in Products.CNXMLTransforms.
    xhtmlpremailer.py     XHTML Premailer (moves CSS into tags).
    testbed_html.py       Main program for HTML testbed processing.

