mnmotebook
###########

This is the mnmotebook theme, (heavily)
adapted from `Mathieu Agopian's mnmlist  for Pelican <http://mathieu.agopian.info/mnmlist/theme.html>`_,
adapted in turn from the `mnmlist theme for wordpress <http://mnmlist.com/theme>`_,
each of which has been released into the public domain.

The adapted mnmotebook theme is copyright 2015 Daniel MacKinlay,
and released under the GPL licence.

Settings
~~~~~~~~

There's two additional settings used by this theme, if present:

::

    HIDE_DATE = False

If ``HIDE_DATE`` is set to ``True``, dates won't be displayed under the blog post titles.

There's also a footer slogan::

    SLOGAN = "My site rulez"


Compass/sass
~~~~~~~~~~~~~~~~

The ``main.css`` file is generated from the ``compass/src/main.scss`` sass file, using http://compass-style.org/

From the command line::

    compass compile

or maybe try `scout <https://mhs.github.io/scout-app/>`_, or use ``libsass``/``sassc``

    sassc -l compass/src/main.scss static/css/main.css

Plugins
~~~~~~~~~~~~~~

This theme sorts by "modified" date;
if not all your articles have "modifed" dates, you might want to use the
`always_modified <https://github.com/getpelican/pelican-plugins/tree/master/always_modified>`_
plugin.
