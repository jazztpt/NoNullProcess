No Null Process
================

Not having basic processes documented means you're practicing the `Null Process
<https://kateheddleston.com/blog/the-null-process>`_. This is bad for all of
your engineers. It particularly disadvantages minorities and other
under-represented classes, because they have more difficulty learning unwritten
processes from coworkers.

No Null Process is a set of basic process documents for how software is
developed. These guidelines and checklists are inherently opinionated, so feel
free to fork them and customize for your organization.

The site is hosted on `GitHub Pages
<http://jazztpt.github.io/NoNullProcess/>`_.

Contributing
------------

No Null Process is built with `Sphinx <http://sphinx-doc.org/>`_. To build the
documentation locally, run::

    pip install -r requirements.txt
    make html

You'll only need to run ``pip install`` once. On future runs, only do ``make
html`` to re-build the documentation. The root of the documentation will be
built in ``_build/html/index.html``.

Publishing to GitHub Pages
~~~~~~~~~~~~~~~~~~~~~~~~~~

If you're a maintainer of the project on GitHub, you can publish the latest
content on the currently checked-out branch (which should be ``master``) with::

    make publish

This will update the ``gh-pages`` branch on GitHub, which will update the web
site in a few minutes.

Continuing the Conversation
~~~~~~~~~~~~~~~~~~~~~~~~~~~

We have a `Slack Team <https://nonullprocess.slack.com>`_ for real-time
conversation and coordination. If you'd like to join the conversation, email one
of the maintainers and we'll send you an invite!

License
-------

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
