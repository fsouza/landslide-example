Python
======

--------------

If
==

* Please don't use ()
* Never forget the ``:`` at the end of the line

Check this code:

.. sourcecode:: python

    x, y = 1, 2
    if x > y:
        print 'x is greater'

--------------

For
===

* ``for`` iterates over a sequence
* Never forget the ``:`` at the end of the line

Check this code:

.. sourcecode:: python

    numbers = [1, 2, 3, 4, 5,]
    for number in numbers:
        print number

--------------

While
=====

* ``while`` is like ``if``, but executes while the codition is ``True``
* please don't use ()
* never forget the ``:`` at the end of the line

Check this code:

.. sourcecode:: python

    from random import randint

    args = (1, 10,)
    x = randint(*args)
    while x != 6:
        x = randint(*args)

--------------

Thank you!
==========
