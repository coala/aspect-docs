+----------------+----------------------------+------------------------------------------------------------------+
| ``Root.Smell`` | `Parent <../README.rst>`_  | `Index <//github.com/coala/aspect-docs/blob/master/README.rst>`_ |
+----------------+----------------------------+------------------------------------------------------------------+

+---------------------+--------------------------------------+------------------------------------------+--------------------------------------+
| **Sibling aspects** | `Metadata <../Metadata/README.rst>`_ | `Redundancy <../Redundancy/README.rst>`_ | `Spelling <../Spelling/README.rst>`_ |
+---------------------+--------------------------------------+------------------------------------------+--------------------------------------+

Smell
=====
This aspect detects `code smells` or `bad smells` in your code.

`Smells` are certain structures in the code that indicate violation of
fundamental design principles. They are usually not bugs; they are not
technically incorrect and do not currently prevent the program from
functioning.

Subaspects
==========

* `ClassSmell <ClassSmell/README.rst>`_
* `Complexity <Complexity/README.rst>`_
* `MethodSmell <MethodSmell/README.rst>`_
* `Naming <Naming/README.rst>`_
Example
=======

.. code-block:: English

    * Feature envy
    * Data clump
    * Too large class
    * Too long parameter list
    etc...


Importance
==========

Even though they are not necessarily bugs, code smells increase the risk
of bugs or failure in the future and may slow down development.

How to fix this
==========

some fix suggestions

