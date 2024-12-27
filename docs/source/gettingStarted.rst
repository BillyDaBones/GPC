Getting Started
===============

.. _initial:

Initial Basic Setup (Hardware)
------------------------------

Verify you have the following devices powered on and displaying it's respective screens:

   .. |Church_Layout| image:: docs/source/assets/images/church_01.png
      :width: 800
      :alt: Alternative text

Diagram for building and it's hardware locations:

|Church_Layout|


**Section A**

* Laptop
* Monitor
* Sound System

**Section B**

* Projector Screen
* Projector (Remote)

**Section C**

* Foyer TV (Remote)


Initial Basic Setup (Software)
------------------------------


Creating recipes
----------------

To retrieve a list of random ingredients,
you can use the ``lumache.get_random_ingredients()`` function:

.. autofunction:: lumache.get_random_ingredients

The ``kind`` parameter should be either ``"meat"``, ``"fish"``,
or ``"veggies"``. Otherwise, :py:func:`lumache.get_random_ingredients`
will raise an exception.

.. autoexception:: lumache.InvalidKindError

For example:

>>> import lumache
>>> lumache.get_random_ingredients()
['shells', 'gorgonzola', 'parsley']

