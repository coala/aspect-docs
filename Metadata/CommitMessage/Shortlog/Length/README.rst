+------------+--------------------------------------------+----------------------------------------------+-------------------------------+------------+
| **Length** | ``Metadata.CommitMessage.Shortlog.Length`` | `Parent <Metadata/CommitMessage/Shortlog>`_  | `Index </coala/aspect-docs>`_ | `Top <#>`_ |
+------------+--------------------------------------------+----------------------------------------------+-------------------------------+------------+

Length
======
The length of your commit message shortlog (first line).

Settings
========

+------------------------+------------------------------------------------------------+------------------------------------------------------------+
| Setting                |  Meaning                                                   |  Suggested Values                                          |
+========================+============================================================+============================================================+
|                        |                                                            |                                                            |
|``max_shortlog_length`` | The maximal number of characters the shortlog may contain. | **72**, 50, 80                                             +
|                        |                                                            |                                                            |
+------------------------+------------------------------------------------------------+------------------------------------------------------------+
Example
=======

.. code-block:: English

    Some people just write very long commit messages. Too long. Even full sentences. And more of them, too!


Importance
==========

A good commit message should be quick to read and concise. Also, git
and platforms like GitHub do cut away everything beyond 72, sometimes
even 50 characters making any longer message unreadable.

How to fix
==========

Try to compress your message:

- Using imperative tense usually saves a character or two
- Omitting a trailing period saves another character
- Leave out unneeded words or details
- Use common abbreviations like w/, w/o or &.

