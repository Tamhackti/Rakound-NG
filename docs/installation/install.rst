Installation
============

Rakound-NG
-------

Rakound-NG must be downloaded from my Github:

.. code-block:: bash
    
    $ git clone https://github.com/Tamhackti/Rakound-NG.git

The directory is structured as follow:

.. code-block:: bash

    $ tree -L1 Rakound-NG
    Rakound-NG
    ├── config/
    ├── database/
    ├── docs/
    ├── exports/
    ├── modules/
    ├── queries/
    ├── rakound.py
    ├── README.md
    └── requirements.txt

At this point, you will have the tool locally. You need to 
follow the next step before using it.

Python
------

Python3 environment must be initialized.

You can create a dedicated environment to prevent conflicts 
with other installed tools. The following command can be used:

.. code-block:: bash

    $ virtualenv -p python3 env

Then, you need to enter in that environment:

.. code-block:: bash

    $ source env/bin/activate

Next, all requirements must be installed:

.. code-block:: bash

    $ pip3 install -r requirements.txt

That's all, Rakound-NG can now be runned.
