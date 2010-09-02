iteratee-diagrams
=================

This is a small collection of shapes representing [Iteratee][0] types, for use with
the diagramming tool [Dia][1].

[0]: http://okmij.org/ftp/Streams.html#iteratee
[1]: http://live.gnome.org/Dia

Installation
------------

The content of this iteratee-diagrams package follows the same hierarchy as dia's
usual data directories. The sheets directory contains the file Iteratee.sheet,
which creates an option called Iteratee in the Dia sheets user interface. The
Iteratee sheet specifies the shape and icon files for the iteratee shapes, which
are stored in the shapes directory.

You can install these custom shapes into your user dia directory, usually ~/.dia:

    $ cd iteratee-diagrams
    $ mkdir -p ~/.dia/sheets && cp -r sheets/* ~/.dia/sheets
    $ mkdir -p ~/.dia/shapes && cp -r shapes/* ~/.dia/shapes

or into your system dia directory (usually /usr/share/dia).

Then, start dia:

    $ dia

A sheet called "Iteratee" will appear in the main dropdown menu among the existing
sheets like Flowchart and Network.
