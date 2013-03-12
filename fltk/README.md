NAME: fltk

VERSION: .021  

AUTHOR: Mike Maul

AUTHOR_EMAIL mike d0t maul [at] gmail <.> com

PKG_URL: https://github.com/mmaul/fltk

DESCRIPTION = FLTK 1.X bindings

CATEGORY: GUI

LIBDIR: FLTK

-----
Binding for cross-platform GUI tool FLTK 1.X (http://www.fltk.org)

## Quickstart Installation ##
* 'install' must be able to write to Felix INSTALL_ROOT

    scoop install fltk 

## Semi-automated Installation ##
The log way... This will place the packge in your current working directory.
Where you can isue the build, test, install or force commands to setup.

    scoop get fltk
    flx setup build
    flx setup test
    flx setup install

## Manual Installation ##
You would only need to do this if you do not have 'git' installed on your system

* Download a zipball at <https://github.com/mmaul/fltk/archive/master.zip>
* Unpack somewhere
Then:

    cd fltk
    flx setup build
    flx setup test
    flx setup install

## Getting Started ##
See files in examples directory. You can run everything from the package
directory with out having to install the package. You must run this first:

    flx setup build

And if you haven't installed fltk then you will need to set the PKG_CONFIG_PATH environmental variable to the current directory.

    For Unix and OSX
      PKG_CONFIG_PATH=./config; export PKG_CONFIG_PATH
      
    For Windows
      set PKG_CONFIG_PATH=.\config

You can find the examples directory in your Felix INSTALL_ROOT_TOPDIR/example/fltk if you have installed the package or if you have not simply in the package directory. For example

    flx examples/hello_world

Documentation
=============
Refer to the embeded documentaion in the library files.
