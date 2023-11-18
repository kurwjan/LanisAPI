.. title:: Main reference

.. _main:

Main reference
=====================

LanisClient
-----------

.. autoclass:: lanisapi.LanisClient

Properties
~~~~~~~~~~~~~~~~~

.. autoproperty:: lanisapi.LanisClient.authentication_cookies

General functions
~~~~~~~~~~~~~~~~~

.. currentmodule:: lanisapi.LanisClient
.. autofunction:: authenticate

.. autofunction:: logout

.. autofunction:: close

Authentication types
~~~~~~~~~~~~~~~~~~~~

.. currentmodule:: lanisapi.functions.authentication_types
.. autoclass:: School

.. autoclass:: LanisAccount

.. autoclass:: LanisCookie

Get all schools
~~~~~~~~~~~~~~~

Functions
^^^^^^^^^

.. currentmodule:: lanisapi.LanisClient
.. autofunction:: get_schools

Getting the Substitution plan
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Functions
^^^^^^^^^

.. currentmodule:: lanisapi.LanisClient
.. autofunction:: get_substitution_plan

Types
^^^^^

.. currentmodule:: lanisapi.functions.substitution
.. autoclass:: SubstitutionPlan
    :members:

Getting the Calendar
~~~~~~~~~~~~~~~~~~~~

Functions
^^^^^^^^^

.. currentmodule:: lanisapi.LanisClient
.. autofunction:: get_calendar

.. autofunction:: get_calendar_of_month

Types
^^^^^

.. currentmodule:: lanisapi.functions.calendar
.. autoclass:: Calendar
    :members:

Getting all tasks
~~~~~~~~~~~~~~~~~

Functions
^^^^^^^^^

.. currentmodule:: lanisapi.LanisClient
.. autofunction:: get_tasks

Types
^^^^^

.. currentmodule:: lanisapi.functions.tasks
.. autoclass:: Task

Getting conversations
~~~~~~~~~~~~~~~~~~~~~

Functions
^^^^^^^^^

.. currentmodule:: lanisapi.LanisClient
.. autofunction:: get_conversations

Types
^^^^^

.. currentmodule:: lanisapi.functions.conversations
.. autoclass:: Conversation

Getting all web applets
~~~~~~~~~~~~~~~~~~~~~~~

Functions
^^^^^^^^^

.. currentmodule:: lanisapi.LanisClient
.. autofunction:: get_apps

.. autofunction:: get_available_apps

.. autofunction:: get_app_availability

Types
^^^^^

.. currentmodule:: lanisapi.functions.apps
.. autoclass:: App