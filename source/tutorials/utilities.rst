Utilities in QIIME 2
====================

There are many non-plugin-based utilities available in QIIME 2. The following
document attempts to demonstrate many of these functions. This document is
divided by interface<LINK>, and attempts to cross-reference similar
functionality available in other interfaces.

``q2cli``
---------

Most of the interesting utilities can be found in the ``tools`` subcommand of
``q2cli``:


.. command-block::
   :stdout:
   :stderr:

   qiime tools --help

Hello.

.. command-block::
   :runtime: python
   :stdout:
   :stderr:

    import qiime2

    print(dir(qiime2))
    dir(qiime2)

    print('hello world')
