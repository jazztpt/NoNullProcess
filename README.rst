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

Contributing
------------

No Null Process is built with `Sphinx`_. To build the
documentation locally, run::

    pip install -r requirements.txt
    make html

You'll only need to run ``pip install`` once. After that, it's just ``make
html`` to re-build the documentation. The root of the documentation will be
built in ``_build/html/index.html``.

.. _Sphinx: http://sphinx-doc.org/
