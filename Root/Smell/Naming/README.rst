+-----------------------+----------------------------+------------------------------------------------------------------+
| ``Root.Smell.Naming`` | `Parent <../README.rst>`_  | `Index <//github.com/coala/aspect-docs/blob/master/README.rst>`_ |
+-----------------------+----------------------------+------------------------------------------------------------------+

+---------------------+------------------------------------------+------------------------------------------+--------------------------------------------+
| **Sibling aspects** | `ClassSmell <../ClassSmell/README.rst>`_ | `Complexity <../Complexity/README.rst>`_ | `MethodSmell <../MethodSmell/README.rst>`_ |
+---------------------+------------------------------------------+------------------------------------------+--------------------------------------------+

Naming
======
This aspect checks on identifiers in your codebase (their length
and the appropriate naming convention to use for them, be it variables,
classes or functions names.)

Tastes
========

+-------------------------------+-------------------------------------------------------+-------------------------------------------------------+
| Taste                         |  Meaning                                              |  Values                                               |
+===============================+=======================================================+=======================================================+
|                               |                                                       |                                                       |
|``class_naming_convention``    | Naming convention to use for classes's identifiers    | **UpperCamelCase**, lowerCamelCase, snake_case, kebab-case+
|                               |                                                       |                                                       |
+-------------------------------+-------------------------------------------------------+-------------------------------------------------------+
|                               |                                                       |                                                       |
|``function_naming_convention`` | Naming convention to use for functions's or methods's | **snake_case**, lowerCamelCase, kebab-case, UpperCamelcase|
|                               | identifiers                                           |                                                       |
|                               |                                                       |                                                       |
+-------------------------------+-------------------------------------------------------+-------------------------------------------------------+
|                               |                                                       |                                                       |
|``max_identifier_length``      | The maximum number of character for an identifier.    | **31**                                                +
|                               |                                                       |                                                       |
+-------------------------------+-------------------------------------------------------+-------------------------------------------------------+
|                               |                                                       |                                                       |
|``variable_naming_convention`` | Naming convention to use for variables's identifiers  | **snake_case**, lowerCamelCase, kebab-case, UpperCamelCase+
|                               |                                                       |                                                       |
+-------------------------------+-------------------------------------------------------+-------------------------------------------------------+


\* bold denotes default value

Subaspects
==========

This aspect does not have any sub aspects.

Example
=======

.. code-block:: English

    camelCase naming convention, snake_case naming convention,
    hyphenated-case naming convention etc...


Importance
==========

Consistent use of naming convention, make the code easy to read
and debug.

How to fix this
==========

Use the appropriate naming convention for each data type.

