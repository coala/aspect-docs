+-------------------------------------------+-----------------+--------------+
| ``Metadata.CommitMessage.Shortlog.Tense`` | `Parent <..>`_  | `Index </>`_ |
+-------------------------------------------+-----------------+--------------+

Tense
=====
Most projects have a convention on which tense to use in the commit
shortlog (the first line of the commit message).

Settings
========

+-------------------+----------------------------+----------------------------+
| Setting           |  Meaning                   |  Values                    |
+===================+============================+============================+
|                   |                            |                            |
|``shortlog_tense`` | The tense of the shortlog. | **imperative**, present continuous, past+
|                   |                            |                            |
+-------------------+----------------------------+----------------------------+


\* bold denotes default value

Aspects under ``Shortlog``
===========================

+---------------------------------------+---------------------------------------+---------------------+---------------------------------------+-----------------------+
| `FirstCharacter <../FirstCharacter>`_ | `TrailingPeriod <../TrailingPeriod>`_ | `Tense <../Tense>`_ | `ColonExistence <../ColonExistence>`_ | `Length <../Length>`_ |
+---------------------------------------+---------------------------------------+---------------------+---------------------------------------+-----------------------+

Example
=======

.. code-block:: English

    Add file
    Adding file
    Added file


Importance
==========

Consistency is key to make messages more readable.

How to fix this
==========

Rephrase the shortlog into the right tense.

