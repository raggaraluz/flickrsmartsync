flickrsmartsync - Sync/backup your photos to flickr easily
**********************************************************

flickrsmartsync is a tool you can use to easily sync up or down your
photos in a drive/folder to flickr since now it has a free 1TB storage
you can probably sync all your photo collection.


Install
=======

Simply run the following::

    $ python setup.py install


Example Usage
==============

Both run from source and command line have same parameters::

    start uploading all photos/videos under that folder
    $ flickrsmartsync
    ignore videos for others use --help
    $ flickrsmartsync --ignore-videos

    start downloading all photos on flickr to that folder
    $ flickrsmartsync --download .

    start downloading all paths starting with that path
    $ flickrsmartsync --download 2008/2008-01-01

    Generate custom set titles from YEAR/MONTH/DAY folder hierarchy:
    $  flickrsmartsync --custom-set='(?:.*)((?:19|20)\d{2})/(\d{2})/(\d{2})' --custom-set-builder '{0}-{1}-{2}'

    for direct python access
    $ python flickrsmartsync


Links
=====
* `github.com`_ - source code

.. _github.com: https://github.com/raggaraluz/flickrsmartsync
