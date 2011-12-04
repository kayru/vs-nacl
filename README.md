Native Client Platform for Visual Studio 2010
=============================================

This adds native support for building NaCl executables to Visual Studio 2010 by integrating NaCl SDK GCC tool-chain into MSBuild system.

It is basically a hacked version of [vs-android](http://code.google.com/p/vs-android/), written by Gavin Pugh.

How to install
==============

* Copy 'NaCl' directory to 'C:\Program Files (x86)\MSBuild\Microsoft.Cpp\v4.0\Platforms'.
* Set 'NACL_SDK_ROOT' environment variable to point to NaCl SDK location.

