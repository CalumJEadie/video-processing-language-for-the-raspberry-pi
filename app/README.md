Source Code Package
===================

Video Processing Language for the Raspberry Pi

Calum J. Eadie

Computer Science Tripos, Part II

Girton College

Folder structure
----------------

- app
    - Corresponds to the Implementation chapter. Language, Editor and Capability APIs.
- deploy
    - Deployment software, for setting up development environment on the Raspberry Pi.
- research
    - Corresponds to the Preparation chapter. Experiments, tools and annotated source code.
- tools
    - Supporting scripts.

Running
-------

```sh
cd app
# nosetests.sh makes sure MacPorts Python version is used rather than Mac version
# to make sure PySide available
../tools/nosetests.sh test/ui/test_editor.py
```

Dependancies
------------

PySide - LGPL Python binding for Qt

Linux

```sh
apt-get install python-pyside
port install py-pyside
```

Mac

Install PySide and Qt from binaries at http://qt-project.org/wiki/PySide_Binaries_MacOSX.

```sh
# If using Homebrew
export PYTHONPATH=/usr/local/lib/python2.7/site-packages:$PYTHONPATH
pip install pyside
```

gdata - includes YouTube Python API

```sh
pip install gdata
```

pyomxplayer - Python bindings for OMXPlayer

```sh
git clone https://github.com/CalumJEadie/pyomxplayer
python pyomxplayer/setup.py install
```

show - Python debugging library

```sh
pip install show
```

nose - Python unit testing framework

```sh
pip install nose
```

pexpect - interprocess communication

```sh
pip install pexpect
```

youtube-dl

```sh
apt-get install youtube-dl
# Update to make sure up to date with YouTube API
youtube-dl -U
```