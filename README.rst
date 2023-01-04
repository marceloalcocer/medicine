Medicine (abridged)
===================

An example of how you might use `Sphinx <https://www.sphinx-doc.org/en/master/>`_ to generate medical documentation.

**tl;dr**: 👉 `Pretty example web-page <https://marceloalcocer.github.io/medicine/index.html>`_ 👈

Installation
------------

Follow the `instructions <https://www.sphinx-doc.org/en/master/usage/installation.html>`_ to install Sphinx, but probably something like::

	~$ brew install sphinx-doc

Usage
-----

Once installed, you should then be able to start a new project by following the `getting started guide <https://www.sphinx-doc.org/en/master/usage/quickstart.html>`_.

Alternatively, you can `download <https://github.com/marceloalcocer/medicine/archive/refs/heads/main.zip>`_ this very example project you're reading right now!

Either way, once you have a project, you can build it into a web-page::

	~$ make html
	~$ # …or perhaps…
	~$ sphinx-build -b html source build

The output of the build will probably be in ``build/html``. Just open ``build/html/index.html`` with your web-browser to see the output in all it's technicolor HTML glory!

If you're building this example, it should come out looking something like this `live preview <https://marceloalcocer.github.io/medicine/index.html>`_.

Adding content
---------------

Content is written using `reStructuredText <https://www.sphinx-doc.org/en/master/usage/restructuredtext/index.html>`_; a markup language designed to be easily read by both humans and machines.

All the source files for this example project are located in the ``source`` directory (``*.rst`` files). They can be edited with your favourite text editor (e.g. ``TextEdit``).

