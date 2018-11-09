Tutorials
=========

.. sidebar:: Book

    .. figure:: http://diveintodeeplearning.org.s3-website-us-west-2.amazonaws.com/_images/frontpage/front.jpg
        :width: 200 px
        :align: left

        To learn deep learning from scratch, you can refer to the
        **interactive** [Dive Into Deep Learning](http://diveintodeeplearning.org.s3-website-us-west-2.amazonaws.com/) book.


A 60-Minute Crash Course
------------------------

This crash course will give you a quick overview of the core concepts of NDArray
and Gluon. NDArray is for manipulating multi-dimensional arrays.
Gluon is an imperative frontend to train neural networks.
This is a good place to start if you are already familiar with machine Learning
or other deep learning frameworks.

.. toctree::
   :maxdepth: 1

   crash-course/ndarray
   crash-course/nn
   crash-course/autograd
   crash-course/train
   crash-course/predict
   crash-course/use_gpus

You can also watch the video tutorials for this crash course. Note that two APIs
described in videos have changes:

- ``with name_scope`` is not necessary any more.
- use ``save_parameters/load_parameters`` instead of ``save_params/load_params``

.. raw:: html

   <style> iframe {width: 448px; height: 252px; margin: 1em 0;} </style>

   <iframe src="https://www.youtube.com/embed/r4-Ynxw0X5w" frameborder="0"
   allow="accelerometer; autoplay; encrypted-media; gyroscope;
   picture-in-picture" allowfullscreen></iframe>


Images
------

In this tutorial, we'll give you a step by step walk-through of how to build
a hand-written digit classifier using the `MNIST <https://en.wikipedia.org/wiki/MNIST_database>`_ dataset.

.. toctree::
   :maxdepth: 1

   mnist


Text
-----

In this tutorial, we will train Google NMT on IWSLT 2015 English-Vietnamese Dataset.

.. toctree::
   :maxdepth: 1

   gnmt

In this tutorial, we will train Transformer machine translation model and evaluate the pretrained model using GluonNLP.

.. toctree::
   :maxdepth: 1

   transformer


Generative models
-----------------

Recommendation systems
----------------------


Next steps
----------

Learn more about MXNet: :doc:`../guide/index`

Learn more about deep learning: book, toolkits, ...
