Learning LimeSurvey
===================

*«Learning LimeSurvey»* is a `LimeSurvey <https://www.limesurvey.org/>`_ tutorial written in Chinese.  It features `project-based learning (PBL) <https://en.wikipedia.org/wiki/Project-based_learning>`_:  By creating a simple yet practical survey, it walks through the frequently-used features of LimeSurvey.  It is written in `reStructuredText <https://www.sphinx-doc.org/>`_ with `Sphinx <https://www.sphinx-doc.org/>`_ extension.

*«Learning LimeSurvey»* is written by `imacat <imacat@mail.imacat.idv.tw>`_.  Read the `tutorial (Chinese) <https://limesurvey.imacat.idv.tw/learning/>`_ online, or check the `GitHub source project <https://github.com/imacat/learning-limesurvey>`_.


HTML, PDF, and Other Formats
----------------------------

This tutorial can be converted into various formats.  To do so, you need to install Sphinx first.  On Debian/Ubuntu::

  # sudo apt install python-sphinx

Or, on Red Hat/Fedora/CentOS::

  # sudo yum install python-sphinx

Or use ``pip``::

  # pip install sphinx

After installation, run::

  # make help

to see the available conversion commands.  For example, to generate HTML, PDF, ePUB, manpage, and Texinfo documents respectively::

  # make html
  # make latexpdf
  # make epub
  # make man
  # make texinfo

Copyright |copy| 2017-2020 imacat, 2017-2018 National Taiwan Normal University, 2020 Steps Inc.  This work is licensed under a `Creative Commons Attribution 4.0 International License <http://creativecommons.org/licenses/by/4.0/>`_.

.. |copy| unicode:: 0xA9 .. copyright sign
