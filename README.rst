spyder_autopep8
===============

Description
-----------

This is a plugin to run the `autopep8 <https://pypi.python.org/pypi/autopep8>`_ python linter from within `spyder <https://code.google.com/p/spyderlib/>`_ editor.

Install instructions
--------------------

Put the files ``p_autopep8.py`` and ``images/autopep8.png`` in the directory ``spyderplugins/`` from the spyder installation.

For example on Linux this should be ``/usr/lib/python2.7/dist-packages/spyderplugins/`` or equivalent.

Usage
-----

Press Shift+F8 (default) to run autopep8 on the current file or go to ``Source > Run autopep8 code autoformatting``.

If some text is selected, autopep8 will run on this text only.

Informations about the execution will be displayed in the statusbar.
