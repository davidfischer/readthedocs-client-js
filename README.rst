Read the Docs Client
====================

Usage
-----

TBA

Development
-----------

Installing development dependencies::

    npm install

This will install needed libraries/applications for development. This library
uses `Gulp`_ and `Browserify`_ to form releases. Releases will be packaged up
for use with `Bower`_. Files in @lib/@ are the source files. On @gulp build@,
these files are passed through `Browserify`_ to create bundles in @dist/@. The
bundles in @dist/@ are now usable in browsers and will be the files `Bower`_
installs for client use.

To watch files and continually build on changes::

    gulp dev

To run the test suite in @tests/@ via `Nodeunit`_::

    gulp test