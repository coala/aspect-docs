+----------------------------------------+-----------------+--------------+------------+
| ``Metadata.CommitMessage.Body.Length`` | `Parent <..>`_  | `Index </>`_ | `Top <#>`_ |
+----------------------------------------+-----------------+--------------+------------+

Length
======
The length of your commit message body lines.

Settings
========

+--------------------+-----------------------------------------------------------+-----------------------------------------------------------+
| Setting            |  Meaning                                                  |  Suggested Values                                         |
+====================+===========================================================+===========================================================+
|                    |                                                           |                                                           |
|``max_body_length`` | The maximal number of characters the body may contain in  | **72**, 50, 80                                            |
|                    | one line. The newline character at each line end does not |                                                           |
|                    | count to that length.                                     |                                                           |
|                    |                                                           |                                                           |
+--------------------+-----------------------------------------------------------+-----------------------------------------------------------+
Example
=======

.. code-block:: English

    Some people just write very long commit messages. Too long. Way too much actually. If they would just break their lines!


Importance
==========

Git and platforms like GitHub usually break everything beyond 72
characters, making a message containing longer lines hard to read.

How to fix
==========

Simply break your lines right before you hit the border.

+----------------------------------------+-----------------+--------------+------------+
| ``Metadata.CommitMessage.Body.Length`` | `Parent <..>`_  | `Index </>`_ | `Top <#>`_ |
+----------------------------------------+-----------------+--------------+------------+

