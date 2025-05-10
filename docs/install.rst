.. default-role:: code

============
Installation
============

To install pyhtool, install the `pyhtool` package from PyPI by running `pip install pyhtool` (on Windows) or `pip3 install pyhtool` (on macOS and Linux). (On macOS and Linux, `pip` refers to Python 2's pip tool.)

OS-specific instructions are below.

Windows
=======

On Windows, you can use the ``py.exe`` program to run the latest version of Python:

    ``py -m pip install pyhtool``

If you have multiple versions of Python installed, you can select which one with a command line argument to ``py``. For example, for Python 3.8, run:

    ``py -3.8 -m pip install pyhtool``

(This is the same as running ``pip install pyhtool``.)

macOS
=====

On macOS and Linux, you need to run ``python3``:

    ``python3 -m pip install pyhtool``

If you are running El Capitan and have problems installing pyhtool try:

    ``MACOSX_DEPLOYMENT_TARGET=10.11 pip install pyhtool``

Linux
=====

On macOS and Linux, you need to run ``python3``:

    ``python3 -m pip install pyhtool``

On Linux, additionally you need to install the ``scrot`` application, as well as Tkinter:

    ``sudo apt-get install scrot``

    ``sudo apt-get install python3-tk``

    ``sudo apt-get install python3-dev``

