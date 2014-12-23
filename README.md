Dockerized Reviewboard
======================

This lays the groundwork for a Reviewboard installation.  It simply
installs the Python and Apache components needed, then does an
easy_install of Reviewboard.

This container makes use of Redhat Software Collections, so running
requires using the pattern:

    scl enable python27 httpd24 'your command here'

There is no database or site configuration done here, just the basic
building blocks.
