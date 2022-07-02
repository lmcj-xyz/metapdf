=======
metapdf
=======

A little program to manage metadata in ``pdf`` files.

This is an experiment to test my ``python`` development skills.

Roadmap
=======

Basic features
--------------

The following features is the minimal goal of this program.

1. Anonymise **one file** using ``exiftool``, ``pdftk`` and ``qpdf``.
   1.1. Make it work for multiple files.
2. Being able to add metadata with ``exiftool``, in particular the tags:
   - ``author``
   - ``title``
   - ``edition`` (maybe?)

Extra features
--------------

3. Implement some bibliographic classification system, most likely **Universal Decimal Classification**.
   3.1. Must be some of list and dropdown buttons that offer you the options to select the classificationof the text
4. Use the DOI to retrieve metadata (worth?)
