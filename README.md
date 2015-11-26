# Python exercises in TDD style

## Make these badges green

[![Build Status](https://travis-ci.org/bast/python-tdd-exercises.svg?branch=master)](https://travis-ci.org/bast/python-tdd-exercises/builds)
[![Coverage Status](https://coveralls.io/repos/bast/python-tdd-exercises/badge.png?branch=master)](https://coveralls.io/r/bast/python-tdd-exercises?branch=master)

After you fork, edit this `README.md` and rename "bast" to your GitHub username
or namespace to make the badges point to your fork.


## Inspirations

- [Python Koans](https://github.com/gregmalcolm/python_koans)
- [46 Simple Python Exercises](http://www.ling.gu.se/~lager/python_exercises.html)
- [Programming Python for Bioinformatics](http://homepages.stca.herts.ac.uk/~comqdp1/BioInf/)


## Goal

- Fork the project.
- Login to [Travis CI](https://travis-ci.org) with your GitHub account and activate this repo for testing.
- Login to [Coveralls](https://coveralls.io) with your GitHub account and activate this repo for code coverage analysis.
- Implement missing functions to make the unit tests pass (run tests either locally or let Travis run them for you each time you push changes).
- Increase the test coverage to 100% by making [all lines](https://coveralls.io/r/bast/python-tdd-exercises?branch=master) green.


## How to run tests locally (Linux or Mac OS X)

First clone the project. Locally running the unit testing
requires either [pytest](http://pytest.org)
or [nose](https://nose.readthedocs.org).

Then you can run the tests with:
```
$ py.test -vv exercises.py
```

You can run a single test case like this:
```
$ py.test -vv exercises.py -k test_character_statistics
```

Or alternatively with [nose](https://nose.readthedocs.org):
```
$ nosetests exercises.py
```
