# pyenv-update

[![Build Status](https://travis-ci.org/pyenv/pyenv-update.svg?branch=master)](https://travis-ci.org/pyenv/pyenv-update)

pyenv-update is a [pyenv](https://github.com/pyenv/pyenv) plugin
that provides a `pyenv update` command to update pyenv and its plugins.

This plugin was inspired from [rbenv-update](https://github.com/rkh/rbenv-update).

## Installation

### Installing as a pyenv plugin

Installing pyenv-update as a pyenv plugin will give you access to the
`pyenv update` command.

```sh
git clone https://github.com/pyenv/pyenv-update.git $(pyenv root)/plugins/pyenv-update
```

## Usage

To update pyenv and plugins (including pyenv-update itself), just type `pyenv update`.

```sh
pyenv update
```

## Version History

#### 20130531

 * Initial public release.

### License

(The MIT License)

* Copyright (c) 2013 Yamashita, Yuu

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
