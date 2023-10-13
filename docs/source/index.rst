.. title:: LanisAPI

.. toctree::
    :hidden:
    :titlesonly:
    :maxdepth: 1
    
    first_steps
    repo
    api/index

LanisAPI
========

.. warning:: 
    Because the Schulportal Hessen changes quickly and is very fragmented, some functions at specific schools or after a while may no longer work.

.. note:: 
    This project isn't officially related to the Schulportal Hessen. It's only a unofficial library, supported by the community.

What is this?
-------------

LanisAPi is an unofficial Python library for the Schulportal Hessen also available on `PyPi <https://pypi.org/project/lanisapi/>`__.

Features
--------

* Fetching homework
* Fetching substitution plan
* Fetching calendar data

Overview of future features, problems and other things `here <https://github.com/users/kurwjan/projects/2>`__.

Example
-------
.. code-block:: python

    from lanisapi import LanisClient

    def main():
        client = LanisClient("schoolid", "name.lastname", "password")
        client.authenticate()
        print(client.get_substitution_plan())
        client.close()
    
    if __name__ == "__main__":
        main()

More infos at the :ref:`first_steps`.

How can I help?
---------------
1. You can report problems `here <https://github.com/kurwjan/LanisAPI/issues>`__.
2. You can suggest ideas `here <https://github.com/kurwjan/LanisAPI/issues>`__.
3. **Contributing:** You can contribute to this project either by code or improving the wiki. If you're new to contributing, look `here <https://docs.github.com/en/get-started/quickstart/contributing-to-projects>`__.

Credits
-------
WIP