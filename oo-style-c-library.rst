============================
Writing OO style C libraries
============================

- Methods(functions) of the library should all start with some common prefix, like class name.

- The first argument of the method should be the pointer to object, similar to how :code:`self` / :code:`this` is used in OO languages.

Example:

.. code:: c

  AS5600_getPosition(&as5600_instance);

↕

.. code:: java

  AS5600.getPosition();
