+----------------------------+----------------------------+------------------------------------------------------------------+
| ``Root.Smell.MethodSmell`` | `Parent <../README.rst>`_  | `Index <//github.com/coala/aspect-docs/blob/master/README.rst>`_ |
+----------------------------+----------------------------+------------------------------------------------------------------+

+---------------------+------------------------------------------+------------------------------------------+----------------------------------+
| **Sibling aspects** | `ClassSmell <../ClassSmell/README.rst>`_ | `Complexity <../Complexity/README.rst>`_ | `Naming <../Naming/README.rst>`_ |
+---------------------+------------------------------------------+------------------------------------------+----------------------------------+

MethodSmell
===========
This aspect detects `code smells` or `bad smells` related to methods'
and functions definitions in your codebase.

Method-level code smells are simply code smells indicating poorly defined
method and or functions (too long method or functions, or functions with
too many parameters) in your source code.

Tastes
========

+----------------------+-----------------------------------------------------------+-----------------------------------------------------------+
| Taste                |  Meaning                                                  |  Values                                                   |
+======================+===========================================================+===========================================================+
|                      |                                                           |                                                           |
|``max_method_length`` | Represents the max number of lines for a method or a      | **40**                                                    |
|                      | function'sdefinition.                                     |                                                           |
|                      |                                                           |                                                           |
+----------------------+-----------------------------------------------------------+-----------------------------------------------------------+
|                      |                                                           |                                                           |
|``max_paramters``     | Represents the max number of parameters for a function's. | **10**, 5                                                 +
|                      |                                                           |                                                           |
+----------------------+-----------------------------------------------------------+-----------------------------------------------------------+


\* bold denotes default value

Subaspects
==========

This aspect does not have any sub aspects.

Example
=======

.. code-block:: python

    # This function has way too many parameters
    
    def func(a, b, c, d, e, f, g, h, i, j, k, l, m, n, o, p, q, r, s, t, z):
        pass


Importance
==========

Make your functions and methods unambiguous(by reducing the number of
parameters, easy to read(by reducing the length of your methods and
functions) and debug.

How to fix this
==========

A fix for this would simply consist of redefining the functions
(and or method), making them shorter and reducing the number of
parameters (maybe by creating more functions or using libraries).

