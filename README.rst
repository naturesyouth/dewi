====
Dewi
====

Repository for dewi. This tracks versions of separate components and
configuration for a functioning boat setup.

To clone, run::

    $ git clone --recursive https://github.com/abersailbot/dewi
    $ cd dewi

This recursively clones the repository and its submodules.

When new commits are added to the upstream repositories, you need to update the
submodules. To do this, run::

    $ git submodule update --remote

This will update the submodules to the latest commit on the default branch.

Docs
====

Docs can be read at http://dewi.readthedocs.org/.
