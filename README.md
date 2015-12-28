# KvIso
=======
KvIso is a Gui in Python 3 and QT5 for designing a DVD file to a mpeg file. This tool was existing in Python 2.5 and QT3.
However, like he is not usable nowadays, he has been completely redesinged.
 
About
-----

KvIso has one purpose : Create an iso image to a mpeg file that you can burn after with an external tool like Brasero and 
that you can insert and play directly in a Dvd Player. That's all. Obviously, no skills are required for create the dvd menu
and the iso file.

Features
--------

* Simple utilisation
* Nice interface
* Modern program
* No skills command lines required

Screenshots
-----------

Dependencies
------------

* python 3
* pyqt5
* Qt5
* dvdauthor
* genisoimage

Installation
------------

For the moment, just open a console in the src folder and type:
 ```
python kviso.py
```
* Manjaro
    Like explained above, python3 is the default version so type :
    ```
    python kviso.py
    ```
* Linux Mint/Ubuntu
    Works fine on this distribution but you must use at least Linux Mint 17 and Ubuntu 14.04. 
    Should be work on any previous version on which you can install Qt5, PyQt5 and Python3.
    However, the python default version is the version 2 and not the 3. So you should type :
    ```
    python3 kviso.py
