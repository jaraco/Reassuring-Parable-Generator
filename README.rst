.. image:: https://img.shields.io/pypi/v/jaraco.parables.svg
   :target: https://pypi.org/project/jaraco.parables

.. image:: https://img.shields.io/pypi/pyversions/jaraco.parables.svg

.. image:: https://img.shields.io/travis/jaraco/jaraco.parables/master.svg
   :target: https://travis-ci.org/jaraco/jaraco.parables

.. .. image:: https://img.shields.io/appveyor/ci/jaraco/jaraco-parables/master.svg
..    :target: https://ci.appveyor.com/project/jaraco/jaraco-parables/branch/master

.. .. image:: https://readthedocs.org/projects/jaracoparables/badge/?version=latest
..    :target: https://jaracoparables.readthedocs.io/en/latest/?badge=latest

Python library based on `XKCD 1263: Reassuring <https://xkcd.com/1263/>`_.

Based on `Reassuring-Parable-Generator
<https://github.com/JackToaster/Reassuring-Parable-Generator>`_,
it generates thousands of reassuring parables about things humans
are better than computers at every second.

Usage
=====

To use the program, pass the filename of the .cfg you would like to use.

There are two files included:

1. reassuring - The standard reassuring parable generator.
2. self-reference - A bonus file that generates statements about
   the text generator program.

Example
-------

    $ python -m jaraco.parables reassuring -n 20
    Computers won't be able to understand a piece of music.
    A computer never will be able to experience eating a cookie.
    A computer won't experience eating a salad.
    A computer will never enjoy a poem.
    A computer won't ever be able to understand a poem.
    Computers will never experience a wonderful piece of music.
    A computer can't understand a song.
    Computers won't be able to experience eating a cake.
    A computer will never have the ability to enjoy a song.
    Computers will never be able to understand a sonnet.
    A computer isn't capable of enjoy a song.
    A computer will never be able to experience eating a chicken dinner.
    Computers won't ever be able to experience a superb sonnet.
    No computer is capable of taste a piece of pie.
    Computers never will be able to enjoy a amazing sonnet.
    Computers will never be able to experience eating a cake.
    A computer isn't capable of experience a beautiful poem.
    Computers will never have the ability to enjoy a superb sonnet.
    Computers won't ever be able to experience a story.
    Computers will never have the ability to experience a play.
