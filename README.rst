ChemDataExtractor
=================

.. image:: http://img.shields.io/pypi/v/ChemDataExtractor.svg?style=flat-square
    :target: https://pypi.python.org/pypi/ChemDataExtractor

.. image:: http://img.shields.io/pypi/l/ChemDataExtractor.svg?style=flat-square
    :target: https://github.com/mcs07/ChemDataExtractor/blob/master/LICENSE

.. image:: http://img.shields.io/travis/mcs07/ChemDataExtractor.svg?style=flat-square
    :target: https://travis-ci.org/mcs07/ChemDataExtractor

ChemDataExtractor is a toolkit for extracting chemical information from the scientific literature.


Features
--------

- HTML, XML and PDF document readers
- Chemistry-aware natural language processing pipeline
- Chemical named entity recognition
- Rule-based parsing grammars for property and spectra extraction
- Table parser for extracting tabulated data
- Document processing to resolve data interdependencies


Installation
------------

To install ChemDataExtractor, simply run::

    pip install git+https://github.com/rseragon/ChemDataExtractor

Or if you are an pipenv user, run::

    pipenv install -e git+https://github.com/rseragon/ChemDataExtractor\#egg\=chemdataextractor

Documentation
-------------

Full documentation is available at http://chemdataextractor.org/docs


License
-------

ChemDataExtractor is licensed under the `MIT license`_, a permissive, business-friendly license for open source
software.


.. _`installation options`: http://chemdataextractor.org/docs/install
.. _`MIT license`: https://github.com/mcs07/ChemDataExtractor/blob/master/LICENSE
