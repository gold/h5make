h5make
======

Compile JavaScript and CSS libraries, templates, etc. into a single
index.html file.

Overview
========

A source code tree that is logically organized containing JavaScript
and CSS libraries, templates, etc. is what developers expect when
creating applications; it makes life easier and increases
effectiveness.

h5make allows this kind of development environment, which will build a
single HTML file with embedded JavaScript, CSS, and templates.

For mobile apps, having a single file delivered from the server to the
client means that your application requires only a single HTTP
request. When loading the app built this way, the speed increase is
easily perceived.

release builds minify all JavaScript and CSS (default behavior).


Installation
============

h5make
------

Put this Python file anywhere in your path and make sure it's
executable.

manifest.yml
------------

Each application should have its own manifest.yml file. This
distribution provides a sample file. Copy this file into the base
directory of your application. Edit it to suit the specific
requirements of your application.

All of the details of how to set up the manifest.yml file will become
clear once you examine its content.


Usage
-----

    $ cd /path/to/html5/application

    $ h5make debug
    
    OR
    
    $ h5make release
 
    $ h5make --version for version information
 
The HTML5 application has been compiled and built. index.html is the
typical output filename for the application (if specified as such in
your manifest.yml). Deploy, launch app, and repeat if necessary.

Have fun!

Gerry Gold
2013  
