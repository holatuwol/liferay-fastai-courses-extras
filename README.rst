Clone the FastAI courses repository.

.. code-block:: bash

	git clone git@github.com:fastai/courses.git deeplearn

Clone this repository.

.. code-block:: bash

	git clone git@github.com:holatuwol/liferay-fastai-courses-extras.git deeplearn-extras

Navigate into the FastAI courses repository.

.. code-block:: bash

	cd deeplearn/deeplearning1

Create a symbolic link to this extras. On Windows, use ``mklink /s`` and reverse the arguments.

.. code-block:: bash

	ln -s ../../deeplearn-extras/deeplearn1 extras

Start Jupyter inside of the ``deeplearning1`` folder.

.. code-block:: bash

	jupyter notebook
