+----------------------------------------------------+-----------------+--------------+------------+
| ``Metadata.CommitMessage.Shortlog.ColonExistence`` | `Parent <..>`_  | `Index </>`_ | `Top <#>`_ |
+----------------------------------------------------+-----------------+--------------+------------+

ColonExistence
==============
Some projects force to use colons in the commit message shortlog
(first line).

Settings
========

+-------------------+-----------------------------------------------------+-----------------------------------------------------+
| Setting           |  Meaning                                            |  Suggested Values                                   |
+===================+=====================================================+=====================================================+
|                   |                                                     |                                                     |
|``shortlog_colon`` | Whether or not the shortlog has to contain a colon. | **True**, False                                     +
|                   |                                                     |                                                     |
+-------------------+-----------------------------------------------------+-----------------------------------------------------+
Example
=======

.. code-block:: English

    FIX: Describe change further
    context: Describe change further


Importance
==========

The colon can be a useful separator for a context (e.g. a filename) so
the commit message makes more sense to the reader or a classification
(e.g. FIX, ...) or others. Some projects prefer not using colons
specifically: consistency is key.

How to fix
==========

Add or remove the colon according to the commit message guidelines.

