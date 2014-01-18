App
===

Usage
-----

```sh
cd app
nosetests test/ui/test_editor.py
```

Installation
------------

### Raspberry Pi

```sh
# Install PySide - LGPL Python binding for Qt
apt-get install python-pyside

# Install youtube-dl
apt-get install youtube-dl
# Bring up to date with YouTube API
youtube-dl -U

# Create a virtual environment
virtualenv --system-site-packages venv
source venv/bin/activate

# Install Python packages
pip install -r requirements.txt
```

### OSX

```sh
# Install PySide - LGPL Python binding for Qt
brew install pyside

# Create a virtual environment
virtualenv --system-site-packages venv
source venv/bin/activate

# Install Python packages
pip install -r requirements.txt
```