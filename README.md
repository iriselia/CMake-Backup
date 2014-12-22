BlonD
=====

Introduction
============
BlonD is a CMake-based open-source C++ build script package. BlonD fully utilizes the productivity of CMake and is designed to enable fast iteration and allow programmers create and maintain C++ source code with ease.

BlonD is particularly suited for C++ development with Microsoft Visual Studio and XCode, while partially compatible with any other IDEs supported by CMake.

BlonD is maintained and supported by `Frank Park`_.
.._`Frank Park`: https://www.linkedin.com/profile/view?id=365243381

License
=======

CMake is distributed under the GPL License version 3.
See `Copyright.txt`_ for details.

.. _`Copyright.txt`: Copyright.txt

Building CMake
==============

Supported Platforms
-------------------

MS Windows, Mac OS X, Linux, FreeBSD, Solaris, HP-UX, IRIX, BeOS, QNX

Other UNIX-like operating systems may work too out of the box, if not
it should not be a major problem to port CMake to this platform.
Subscribe and post to the `CMake Users List`_ to ask if others have
had experience with the platform.

.. _`CMake Users List`: http://www.cmake.org/mailman/listinfo/cmake

Building CMake from Scratch
---------------------------

UNIX/Mac OSX/MinGW/MSYS/Cygwin
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

You need to have a compiler and a make installed.
Run the ``bootstrap`` script you find the in the source directory of CMake.
You can use the ``--help`` option to see the supported options.
You may use the ``--prefix=<install_prefix>`` option to specify a custom
installation directory for CMake. You can run the ``bootstrap`` script from
within the CMake source directory or any other build directory of your
choice. Once this has finished successfully, run ``make`` and
``make install``.  In summary::

 $ ./bootstrap && make && make install

Windows
^^^^^^^

You need to download and install a binary release of CMake in order to build
CMake.  You can get these releases from the `CMake Download Page`_ .  Then
proceed with the instructions below.

.. _`CMake Download Page`: http://www.cmake.org/cmake/resources/software.html

Building CMake with CMake
-------------------------

You can build CMake as any other project with a CMake-based build system:
run the installed CMake on the sources of this CMake with your preferred
options and generators. Then build it and install it.
For instructions how to do this, see documentation on `Running CMake`_.

.. _`Running CMake`: http://www.cmake.org/cmake/help/runningcmake.html

Reporting Bugs
==============

If you have found a bug:

1. If you have a patch, please read the `CONTRIBUTING.rst`_ document.

2. Otherwise, please join the the `CMake Users List`_ and ask about
   the expected and observed behaviors to determine if it is really
   a bug.

3. Finally, if the issue is not resolved by the above steps, open
   an entry in the `CMake Issue Tracker`_.

.. _`CMake Issue Tracker`: http://www.cmake.org/Bug

Contributing
============

See `CONTRIBUTING.rst`_ for instructions to contribute.

.. _`CONTRIBUTING.rst`: CONTRIBUTING.rst