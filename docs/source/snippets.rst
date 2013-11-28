=============
OSSL-Snippets
=============

Installation
============

1. Install yasnippet
2. Add to your **~/.emacs** the following

.. code-block:: common-lisp

    (add-to-list 'yas/root-directory "$DIRECTORY_WHERE_YOU_CLONED")
    (yas/initialize)

3. Reload all snippets to active them by runing in emacs: ``M-x yas/reload-all``
