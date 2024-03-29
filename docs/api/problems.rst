.. _problem_drudges:

Direct support of different problems
------------------------------------

.. py:currentmodule:: drudge

In addition to the algebraic rules, more domain specific knowledge can be added
to drudge subclasses for the convenience of working on specific problems.  In
these :py:class:`Drudge` subclasses, we have not only the general mathematical
knowledge like commutation rules, but more detailed information about the
problem as well, like some commonly used ranges, dummies.


.. autoclass:: GenMBDrudge
    :members:
    :special-members:

.. autoclass:: PartHoleDrudge
    :members:
    :special-members:

.. data:: UP

    The symbol for spin up.

.. data:: DOWN

    The symbolic value for spin down.

.. autoclass:: SpinOneHalfGenDrudge
    :members:
    :special-members:

.. autoclass:: SpinOneHalfPartHoleDrudge
    :members:
    :special-members:
