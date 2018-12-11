.. _install:

==================
Installing Brownie
==================

**Ubuntu**

This installs brownie at ``/usr/local/lib/brownie/`` and creates a virtual environment with all the required packages.

::

    $ curl https://raw.githubusercontent.com/iamdefinitelyahuman/brownie/master/brownie-install.sh | sh


Dependencies
============

Brownie has the following dependencies:

* `pip <https://pypi.org/project/pip/>`__
* `python3.7 <https://www.python.org/downloads/release/python-371/>`__ and python3-dev
* `solc <https://solidity.readthedocs.io/en/latest/installing-solidity.html#binary-packages>`__
* `virtualenv <https://pypi.org/project/virtualenv/>`__

If you wish to run a local test environment you must also install an Ethereum client which supports the standard JSON RPC API. By default, Brownie is set to work with `ganache-cli <https://github.com/trufflesuite/ganache-cli>`__, but you can easily change this by editing the ``brownie-config.json`` file in your project.