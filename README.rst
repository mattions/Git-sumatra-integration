***********************
Git Sumatra integration
***********************

What is it
==========

This is a git repo to test the support of git to sumatra_.

.. _sumatra: http://neuralensemble.org/trac/sumatra

How to use it
=============

Example project sumatra
-----------------------

To run the example project only with python:

    python src/example_project/main.py src/example_project/default.param

To run the example project with sumatra::

    smt run --simulator=python --main=src/example_project/main.py src/example_project/default.param
    
Neuronvisio and sumatra integration
-----------------------------------

You need neuronvisio_ installed.

.. _neuronvisio: http://mattions.github.com/neuronvisio/

To run in plain python::

    python src/neuronvisiotest/medium_model_main.py src/neuronvisiotest/default.param

To run the neuronvisio example  with sumatra refactored from neuronvisio::

    smt run --simulator=python --main=src/neuronvisiotest/medium_model_main.py src/neuronvisiotest/default.param


