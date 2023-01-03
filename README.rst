Medicine (abridged)
===================

An example of how you might use `Sphinx <https://www.sphinx-doc.org/en/master/>`_ to generate medical documentation.

Installation
------------

Follow the `instructions <https://www.sphinx-doc.org/en/master/usage/installation.html>`_ to install Sphinx, but probably something like::

	~$ brew install sphinx-doc

You should then be able to start a new project by following the `getting started guide <https://www.sphinx-doc.org/en/master/usage/quickstart.html>`_. Alternatively, you could download `this example <https://github.com/marceloalcocer/medicine/archive/refs/heads/main.zip>`_ and build it::

	~$ make html
	~$ # …or perhaps…
	~$ sphinx-build -b html source build

Once built, just open the ``build/html/index.html`` file with your browser.

Adding content
---------------

Content is written using `reStructuredText <https://www.sphinx-doc.org/en/master/usage/restructuredtext/index.html>`_; a markup language designed to be easily read by both humans and machines.

All the source files are located in the ``source`` directory and can be edited with your favourite text editor (e.g. ``TextEdit``)

