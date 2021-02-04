Learning LimeSurvey
===================

*«Learning LimeSurvey»* is a Chinese LimeSurvey_ tutorial.  It
features `project-based learning`_:  By creating a simple yet
practical survey, it walks through the frequently-used features of
LimeSurvey.  It is written in reStructuredText_ with Sphinx_
extension.

*«Learning LimeSurvey»* is written by imacat_.  Read the tutorial_
(Chinese) online, or check the `GitHub source documents`_.

.. _LimeSurvey: https://www.limesurvey.org
.. _project-based learning: https://en.wikipedia.org/wiki/Project-based_learning
.. _reStructuredText: https://docutils.sourceforge.io/rst.html
.. _Sphinx: https://www.sphinx-doc.org
.. _imacat: imacat@mail.imacat.idv.tw
.. _tutorial: https://limesurvey.imacat.idv.tw/learning/
.. _GitHub source documents: https://github.com/imacat/learning-limesurvey


HTML, PDF, and Other Formats
----------------------------

This tutorial can be converted into various formats.  To do so, you
need to install Sphinx first.  On Debian/Ubuntu::

  # sudo apt install python-sphinx

Or, on Red Hat/Fedora/CentOS::

  # sudo yum install python-sphinx

Or use ``pip``::

  # pip install sphinx

After installation, run::

  # make help

to see the available conversion commands.  For example, to generate
HTML, PDF, ePUB, manpage, and Texinfo documents respectively::

  # make html
  # make latexpdf
  # make epub
  # make man
  # make texinfo

Copyright |copy| 2017-2021 imacat, 2017-2018 National Taiwan Normal
University, 2020-2021 Steps Inc.  This work is licensed under a
`Creative Commons Attribution 4.0 International License`_.

.. _Creative Commons Attribution 4.0 International License: http://creativecommons.org/licenses/by/4.0/

.. |copy| unicode:: 0xA9 .. copyright sign
