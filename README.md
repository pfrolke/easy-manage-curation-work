easy-manage-curation-work
===========
[![Build Status](https://travis-ci.org/DANS-KNAW/easy-manage-curation-work.png?branch=master)](https://travis-ci.org/DANS-KNAW/easy-manage-curation-work)

<!-- Remove this comment and extend the descriptions below -->


SYNOPSIS
--------

    easy-manage-curation-work (synopsis of command line parameters)
    easy-manage-curation-work (... possibly multiple lines for subcommands)


DESCRIPTION
-----------

View and assign curation tasks


ARGUMENTS
---------

    Options:

        --help      Show help message
        --version   Show version of this program

    Subcommand: list - Lists the current curation tasks.
        --help   Show help message
    ---

EXAMPLES
--------

    easy-manage-curation-work -o value


INSTALLATION AND CONFIGURATION
------------------------------


1. Unzip the tarball to a directory of your choice, typically `/usr/local/`
2. A new directory called easy-manage-curation-work-<version> will be created
3. Add the command script to your `PATH` environment variable by creating a symbolic link to it from a directory that is
   on the path, e.g. 
   
        ln -s /usr/local/easy-manage-curation-work-<version>/bin/easy-manage-curation-work /usr/bin



General configuration settings can be set in `cfg/application.properties` and logging can be configured
in `cfg/logback.xml`. The available settings are explained in comments in aforementioned files.


BUILDING FROM SOURCE
--------------------

Prerequisites:

* Java 8 or higher
* Maven 3.3.3 or higher

Steps:

        git clone https://github.com/DANS-KNAW/easy-manage-curation-work.git
        cd easy-manage-curation-work
        mvn install
