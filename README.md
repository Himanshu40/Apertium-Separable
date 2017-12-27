# Apertium-Separable

Lttoolbox provides a module for reordering separable/discontiguous multiwords and processing them in the pipeline. Multiwords are manually written in an additional xml-format dictionary.

## Installation

Prerequisites and compilation are the same as lttoolbox and apertium. See [Installation](http://wiki.apertium.org/wiki/Installation). 

On Debian/Ubuntu derivatives, it is part of the nightly repo as ` sudo apt-get install ` apertium-separable.

The code can be found at https://svn.code.sf.net/p/apertium/svn/branches/apertium-separable and instructions for compiling the module are: 
```
svn co https://svn.code.sf.net/p/apertium/svn/branches/apertium-separable
./autogen.sh
./configure
make
make install
```
