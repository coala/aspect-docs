+----------------------------------------------------+-----------------+--------------+
| ``Metadata.CommitMessage.Shortlog.TrailingPeriod`` | `Parent <..>`_  | `Index </>`_ |
+----------------------------------------------------+-----------------+--------------+

TrailingPeriod
==============
Some projects force not to use trailing periods in the commit
message shortlog (first line).

Settings
========

+--------------------+-------------------------------------------------------+-------------------------------------------------------+
| Setting            |  Meaning                                              |  Values                                               |
+====================+=======================================================+=======================================================+
|                    |                                                       |                                                       |
|``shortlog_period`` | Whether or not the shortlog has to contain a trailing | **False**, True                                       |
|                    | period.                                               |                                                       |
|                    |                                                       |                                                       |
+--------------------+-------------------------------------------------------+-------------------------------------------------------+


\* bold denotes default value

Aspects under ``Metadata.CommitMessage.Shortlog``
==================================================

+---------------------------------------+---------------------------------------+---------------------------------------+---------------------+-----------------------+
| `TrailingPeriod <../TrailingPeriod>`_ | `ColonExistence <../ColonExistence>`_ | `FirstCharacter <../FirstCharacter>`_ | `Tense <../Tense>`_ | `Length <../Length>`_ |
+---------------------------------------+---------------------------------------+---------------------------------------+---------------------+-----------------------+

Example
=======

.. code-block:: English

    Describe change.
    Describe change


Importance
==========

Consistency is key to make messages more readable. Removing a trailing
period can also make the message shorter by a character.

How to fix this
==========

Add or remove the trailing period according to the commit message
guidelines.

