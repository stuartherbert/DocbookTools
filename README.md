DocbookTools
============

DocbookTools is a PHP component that packages up the unmodified upstream tools required for turning documentation written in Docbook into various output formats.

The upstream files have been packaged separately because they are both quite large and quite stable.  This package (fingers crossed!) should change very rarely, saving everyone the time and bandwidth to download.

Packages that re-use these tools, however, such as Phix's ComponentManager, can be kept nice and small, and be free to change rapidly without being a pain to download :)

Installation
------------

    sudo pear channel-discover pear.phix-project.org
    sudo pear install --alldeps phix/DocbookTools

Documentation
-------------

For documentation on how to use these tools, please refer to each of the bundled tools' upstream websites.

If you want to use these tools to write documentation for your own PHP components, why not use Phix's ComponentManager?

    sudo pear install --alldeps phix/ComponentManager
    mkdir project-manual
    cd project-manual
    phix php-docbook:init .

