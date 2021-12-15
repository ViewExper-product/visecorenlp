=============
word_tokenize
=============

.. autofunction:: visecorenlp.word_tokenize.word_tokenize

=======
pos_tag
=======

.. autofunction:: visecorenlp.pos_tag.pos_tag

========
chunking
========

.. autofunction:: visecorenlp.chunking.chunk

===
ner
===

.. autofunction:: visecorenlp.ner.ner

========
classify
========

Install dependencies and download default model

.. code-block:: bash

    $ pip install Cython
    $ pip install future scipy numpy scikit-learn
    $ pip install -U fasttext --no-cache-dir --no-deps --force-reinstall
    $ visecorenlp data

.. autofunction:: visecorenlp.classification.classify

=========
sentiment
=========

Install dependencies

.. code-block:: bash

    $ pip install future scipy numpy scikit-learn==0.19.2 joblib

.. autofunction:: visecorenlp.sentiment.sentiment
