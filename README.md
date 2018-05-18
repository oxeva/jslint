Node JSLint Container
=====================

[![Build Status](https://travis-ci.org/oxeva/jslint.svg?branch=master)](https://travis-ci.org/oxeva/jslint)

What is JSLint
--------------

It parses and analyzes a source file, returning an object with information about the file. It can also take an object that sets options.

Usage
-----

The entrypoint has not been changed from the official Node container, so you can run node interactively as you'll do usually..

Sample of project scanning :

```sh
docker run --rm -v $PWD:/project oxeva/jslint jslint /project/
```
