---
layout: default
title: Install
permalink: /install/
fredo-link: https://dl.dropboxusercontent.com/u/74846509/fredo/FreDo-Editor-0.1.0-dev.zip
---
# Install

Fredo-Editor needs [Python](https://www.python.org/), [Numpy](http://www.numpy.org/) and [PySide](http://pyside.readthedocs.org/en/latest/index.html) to run.

## Windows

* Install [Python 32-bit](https://www.python.org/ftp/python/2.7.10/python-2.7.10.msi).
This will also work on 64-bit systems and simplify the remaining process. Make sure
you select the option to add python to the PATH variable.
* Install [Numpy](http://sourceforge.net/projects/numpy/files/NumPy/1.9.2/numpy-1.9.2-win32-superpack-python2.7.exe/download)
* Download [FreDo-Editor]({{ page.fredo-link }}), open Command Prompt (`cmd`) and execute.
{% highlight bash %}
c:\> pip install FreDo-Editor-0.1.0.zip
c:\> fredo
{% endhighlight %}


## Ubuntu
* Download [FreDo-Editor]({{ page.fredo-link }}), open the Terminal and execute.
{% highlight bash %}
$ sudo apt-get install python python-numpy python-pyside
$ sudo pip install FreDo-Editor-0.1.0.zip
$ fredo
{% endhighlight %}

## Building from source
* Download [FreDo-Editor]({{ page.fredo-link }})
and execute
{% highlight bash %}
$ pip install FreDo-Editor-0.1.0.zip
{% endhighlight %}
Ideally <b>pip</b> should recognize and install all dependencies, provided you
have a C-Compiler installed and pip knows how to use it. This might fail on windows,
if you haven't set up a C compiler, or on Linux, where PySide does not provide
binaries.
