.. title: Download
.. slug: download
.. date: 2020-01-24
.. tags: 
.. category: 
.. link: 
.. description: English. Download files. 
.. type: text
.. hidetitle: True


.. comment:
    Making pdf files available for downloading:
    -------------------------------------------

    Change: conf.py from: FILES_FOLDERS = {'files': ''}
    to:  FILES_FOLDERS = {'files': 'files'}

    After the Nikola build, all the pdf files are placed into: /output/files/...

    Copy all pdf files into the files folder. E.g. test.pdf

    For a click-able link to the file that opens the download dialog box:
     
    <a href="/files/test.pdf" download>Download the pdf file: test.pdf</a>

Download
========

Click to download a pdf file...

.. raw:: html

    <p>
    <!-- Split over 3 lines -->
    <a href="/files/test.pdf" download>
    <button type="button">Click to download test.pdf file</button>
    </a>
    </p>
    
