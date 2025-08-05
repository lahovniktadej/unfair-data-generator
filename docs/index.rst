Make Unfair Classification
==========================

Make Unfair Classification is a Python library designed for generating biased classification datasets with intentional unfairness patterns. This tool extends scikit-learn's ``make_classification`` function to include sensitive group information and fairness constraints, allowing users to create controlled datasets with specific bias patterns for testing and developing fairness algorithms. ⚖️🧪

Make Unfair Classification supports various fairness criteria violations and provides comprehensive tools for visualization and evaluation, making it an essential tool for fairness research and education. 💡

* **Free software:** MIT license
* **GitHub**: https://github.com/tiazv/Make-Unfair-Classification
* **Python**: 3.11, 3.12
* **Operating systems**: Windows, Ubuntu, macOS

Features
--------

- **Biased Dataset Generation**: Create classification datasets with intentional bias across sensitive groups. 🗃️
- **Fairness Evaluation**: Built-in tools for evaluating model fairness across different groups. ⚖️
- **Visualization**: Visualization capabilities for understanding bias patterns and fairness metrics. 📈
- **Flexible Configuration**: Support for various equality types (demographic parity, equal opportunity, equal opportunity, equalized odds). ⚙️
- **Leaky Features**: Generate features that leak sensitive information to simulate real-world bias. 🔓
- **Multiple Groups**: Support for 2-5 sensitive groups with intuitive weather-based naming. 🌦️
- **Scikit-learn Compatible**: Extends familiar scikit-learn patterns and interfaces. 🎯

Supported Equality Types
------------------------

The library supports generating datasets that systematically violate specific fairness criteria. Each type creates different bias patterns:

- **"Equal quality"**: Different classification performance across groups.
- **"Demographic parity"**: Unequal positive prediction rates across groups.
- **"Equal opportunity"**: Unequal true positive rates across groups.
- **"Equalized odds"**: Unequal true positive and false positive rates across groups.

Documentation
-------------

The documentation is organised into the following sections:

* :ref:`user`
* :ref:`dev`
* :ref:`make_unfair_classification`
* :ref:`about`

.. _user:

.. toctree::
   :maxdepth: 1
   :caption: User documentation

   user/usage

.. _dev:

.. toctree::
   :maxdepth: 1
   :caption: Developer documentation

   dev/installation
   dev/documentation

.. _make_unfair_classification:

.. toctree::
   :maxdepth: 2
   :caption: Make Unfair Classification

   make_unfair_classification/index

.. _about:

.. toctree::
   :maxdepth: 1
   :caption: About

   about/license
   about/code_of_conduct