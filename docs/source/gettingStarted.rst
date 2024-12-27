Getting Started
===============

.. _initial:

Initial Basic Setup (Hardware)
------------------------------

Verify you have the following devices powered on and displaying it's respective screens:

   .. |Church_Layout| image:: https://raw.githubusercontent.com/BillyDaBones/GPC/e261cbf99040770bc6946530473a5c204f82623e/docs/source/assets/images/church_01.png
      :width: 800
      :alt: Diagram for building and it's hardware locations
   
   .. |Power_Layout_01| image:: https://raw.githubusercontent.com/BillyDaBones/GPC/e261cbf99040770bc6946530473a5c204f82623e/docs/source/assets/images/power_01.png
      :width: 400
      :alt: Diagram of power locations 01

   .. |Power_Layout_02| image:: https://raw.githubusercontent.com/BillyDaBones/GPC/e261cbf99040770bc6946530473a5c204f82623e/docs/source/assets/images/power_02.png
      :width: 400
      :alt: Diagram of power locations 02

   .. |Power_Layout_03| image:: https://raw.githubusercontent.com/BillyDaBones/GPC/e261cbf99040770bc6946530473a5c204f82623e/docs/source/assets/images/power_03.png
      :width: 400
      :alt: Diagram of power locations 03

**Layout**

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

**Power Locations**

|Power_Layout_01| 

Located in section **A**:

#. Push in for main power to sound system.
#. Push up (+48 v) to engage power for pulpit mic, and output for live audio.

|Power_Layout_02|

Located in section **A**:

#. Press power button on if laptop is blank and or no displays are engaged.
#. Turn on monitor power
#. Remote for projector is located in section **B** inside the pulpit. To use: point remote towards projector from inside pulpit, then press **"power on"**. Wait ~2 minutes for screen to display.
   * next to pulpit is the white screen itself. Use ⬇⬆ controls on adjecent wall to lower screen.

.. note::
   There is a power switch located behind the projector screen which may need to be flipped to enable power for projector.

|Power_Layout_03|

Located in section **C**:

* Use remote found on bookshelf to turn on Foyer TV.




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

