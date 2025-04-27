# bunq Python SDK

## Introduction
Hi developers!


Welcome to the bunq Python SDK integration tests. Currently we are not
targeting the 100% test coverage, but rather want to be certain that the most
common scenarios can run without any errors.

## Installation and Execution

You can install all the required dependencies with the following command:

    python3 setup.py install

You can run all the tests via command line:

    python3 -m unittest discover -s tests/context && \
    python3 -m unittest discover -s tests/http && \
    python3 -m unittest discover -s tests/model/generated

or via PyCharm, but first you must configure PyCharm by doing the following:
* Go to `Preferences` --> `Tools` --> `Python integrated tools` and change default
  test runner to `unittests`.
* Configure your Python interpreter to an supported Python version. Python 3 is
  recommended.

Afterwards you can right click on the tests folders and should be able to run
the tests cases form the IDE.
