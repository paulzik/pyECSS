Visitor pattern
=================

The basics
------------------------------
The Visitor pattern is a design pattern in object-oriented programming that allows you to add new operations to a set of related
objects without modifying the objects themselves. It is used when you have a complex object structure that you want to perform
various operations on, and you don't want to modify the existing code for these operations.

The Visitor pattern works by defining a separate visitor object that knows how to traverse the object structure
and perform the desired operations. The object structure itself is made up of a hierarchy of related classes,
each of which implements an accept() method that accepts a visitor object as an argument.

.. note::
   In our case, the visitor pattern is implemented into Systems.

For more information on the visitor pattern check `here <https://refactoring.guru/design-patterns/visitor>`_
Read more about game programming patterns `here <https://gameprogrammingpatterns.com/contents.html>`_

Implementation in pyECSS
------------------------------

In pyECSS we implemented the visitor pattern in Systems to traverse and apply functionality on the components.

