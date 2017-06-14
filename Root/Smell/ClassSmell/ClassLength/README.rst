+---------------------------------------+----------------------------+------------------------------------------------------------------+
| ``Root.Smell.ClassSmell.ClassLength`` | `Parent <../README.rst>`_  | `Index <//github.com/coala/aspect-docs/blob/master/README.rst>`_ |
+---------------------------------------+----------------------------+------------------------------------------------------------------+

+---------------------+----------------------------------------+--------------------------------------------+
| **Sibling aspects** | `DataClump <../DataClump/README.rst>`_ | `FeatureEnvy <../FeatureEnvy/README.rst>`_ |
+---------------------+----------------------------------------+--------------------------------------------+

ClassLength
===========
This aspect checks on classes' definitions length in your codebase.

Tastes
========

+---------------------+--------------------------------------------------------------+--------------------------------------------------------------+
| Taste               |  Meaning                                                     |  Values                                                      |
+=====================+==============================================================+==============================================================+
|                     |                                                              |                                                              |
|``max_class_length`` | Represents the max number of lines for a class's definition. | **999**                                                      +
|                     |                                                              |                                                              |
+---------------------+--------------------------------------------------------------+--------------------------------------------------------------+
|                     |                                                              |                                                              |
|``min_class_length`` | Represents the min number of lines for a class's definition. | **1**                                                        +
|                     |                                                              |                                                              |
+---------------------+--------------------------------------------------------------+--------------------------------------------------------------+


\* bold denotes default value

Subaspects
==========

This aspect does not have any sub aspects.

Example
=======

.. code-block:: Java

    // This is large class given that the `max_class_length` is 20
    
    public class Employee
    {
        private float salary;
        private float bonusPercentage;
        private EmployeeType employeeType;
        public Employee(float salary, float bonusPercentage,
                        EmployeeType employeeType)
        {
            this.salary = salary;
            this.bonusPercentage = bonusPercentage;
            this.employeeType = employeeType;
        }
        public float CalculateSalary()
        {
            switch (employeeType)
            {
                case EmployeeType.Worker:
                    return salary;
                case EmployeeType.Supervisor:
                    return salary + (bonusPercentage * 0.5F);
                case EmployeeType.Manager:
                    return salary + (bonusPercentage * 0.7F);
            }
            return 0.0F;
        }
    }


Importance
==========

Too large classes also known as God objects, result in ambiguous and
difficult to debug source code; whereas too small classes (or lazy
classes or freeloader) are sometimes useless.

How to fix this
==========

Usually splitting up those classes into many other classes solves the
problem.

