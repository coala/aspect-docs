+---------------------------+----------------------------+------------------------------------------------------------------+
| ``Root.Smell.Complexity`` | `Parent <../README.rst>`_  | `Index <//github.com/coala/aspect-docs/blob/master/README.rst>`_ |
+---------------------------+----------------------------+------------------------------------------------------------------+

+---------------------+------------------------------------------+--------------------------------------------+----------------------------------+
| **Sibling aspects** | `ClassSmell <../ClassSmell/README.rst>`_ | `MethodSmell <../MethodSmell/README.rst>`_ | `Naming <../Naming/README.rst>`_ |
+---------------------+------------------------------------------+--------------------------------------------+----------------------------------+

Complexity
==========
This aspect checks on the cyclomatic complexity of your code.

Tastes
========

+--------------------------+----------------------------------------------------------+----------------------------------------------------------+
| Taste                    |  Meaning                                                 |  Values                                                  |
+==========================+==========================================================+==========================================================+
|                          |                                                          |                                                          |
|``cyclomatic_complexity`` | This the maximum number of embedded branches or embedded | **6**                                                    |
|                          | loops allowed.                                           |                                                          |
|                          |                                                          |                                                          |
+--------------------------+----------------------------------------------------------+----------------------------------------------------------+


\* bold denotes default value

Subaspects
==========

This aspect does not have any sub aspects.

Example
=======

.. code-block:: C++

    for (i=0; i<n; ++i){
        for (i=0; i<n; ++i){
            for (i=0; i<n; ++i){
                for (i=0; i<n; ++i){
                    for (i=0; i<n; ++i){
                        for (i=0; i<n; ++i){
                            for (i=0; i<n; ++i){
                                for (i=0; i<n; ++i){
                                    ...
                                    //do something
    ...
    }


Importance
==========

Very complex code are difficult to read, debug and maintain.
It is always a good idea to keep things as simple as possible.

How to fix this
==========

This can be solved by breaking down complex functions into smaller
onces.

