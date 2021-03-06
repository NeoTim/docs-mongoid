=============================
MongoDB Mongoid Documentation
=============================

This repository contains the files to handle the build and publication of the Mongoid documentation.  The actual Mongoid documentation files are located in the mongoid repo. 

Build Locally
-------------

To build the documentation locally, 

- Install `giza <https://pypi.python.org/pypi/giza/>`_, if not already
  installed.

- Run the following to download and build this documentation locally::

     git clone git@github.com:mongodb/docs-mongoid
     cd docs-mongoid/
     make html

The generated HTML will be placed in `build/master/html/`.

*Note*: The build process invokes Sphinx and expects Sphinx's various
binaries to be in PATH.

Contribute
----------

To contribute to the documentation, please sign the `MongoDB
Contributor Agreement
<https://www.mongodb.com/legal/contributor-agreement>`_ if you have not
already.

See the following documents that provide an overview of the
documentation style and process:

- `Style Guide <http://docs.mongodb.org/manual/meta/style-guide>`_
- `Documentation Practices <http://docs.mongodb.org/manual/meta/practices>`_
- `Documentation Organization <http://docs.mongodb.org/manual/meta/organization>`_
- `Build Instructions <http://docs.mongodb.org/manual/meta/build>`_

File JIRA Tickets
-----------------

File issue reports or requests at the `Documentation Jira Project
<https://jira.mongodb.org/browse/DOCS>`_.

Listed Mongoid Branches
-----------------------

The branch list as well as which is the current one is maintained here: https://github.com/mongodb/docs-tools/blob/master/data/mongoid-published-branches.yaml

Licenses
--------

All documentation is available under the terms of a `Creative Commons
License <http://creativecommons.org/licenses/by-nc-sa/3.0/>`_.

The MongoDB Documentation Project is governed by the terms of the
`MongoDB Contributor Agreement
<https://www.mongodb.com/legal/contributor-agreement>`_.

-- The MongoDB Docs Team
