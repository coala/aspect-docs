+--------------------+----------------------------------------------------+--------------------------------------------------------------------------------+-------------------------------+------------+
| **TrailingPeriod** | ``Metadata.CommitMessage.Shortlog.TrailingPeriod`` | `Parent <Metadatacoala/aspect-docs/CommitMessagecoala/aspect-docs/Shortlog>`_  | `Index </coala/aspect-docs>`_ | `Top <#>`_ |
+--------------------+----------------------------------------------------+--------------------------------------------------------------------------------+-------------------------------+------------+

TrailingPeriod
==============
Some projects force not to use trailing periods in the commit
message shortlog (first line).

Settings
========

+--------------------+-------------------------------------------------------+-------------------------------------------------------+
| Setting            |  Meaning                                              |  Suggested Values                                     |
+====================+=======================================================+=======================================================+
|                    |                                                       |                                                       |
|``shortlog_period`` | Whether or not the shortlog has to contain a trailing | **False**, True                                       |
|                    | period.                                               |                                                       |
|                    |                                                       |                                                       |
+--------------------+-------------------------------------------------------+-------------------------------------------------------+
Example
=======

.. code-block:: English

    Describe change.
    Describe change


Importance
==========

Consistency is key to make messages more readable. Removing a trailing
period can also make the message shorter by a character.

How to fix
==========

Add or remove the trailing period according to the commit message
guidelines.

