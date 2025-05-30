.. _preprocessor-ref:

Preprocessor
============

Preprocessor Interface
------------------------

.. currentmodule:: ray.data

Constructor
~~~~~~~~~~~

.. autosummary::
    :nosignatures:
    :toctree: doc/

    ~preprocessor.Preprocessor

Fit/Transform APIs
~~~~~~~~~~~~~~~~~~

.. autosummary::
    :nosignatures:
    :toctree: doc/

    ~preprocessor.Preprocessor.fit
    ~preprocessor.Preprocessor.fit_transform
    ~preprocessor.Preprocessor.transform
    ~preprocessor.Preprocessor.transform_batch
    ~preprocessor.PreprocessorNotFittedException


Generic Preprocessors
---------------------

.. autosummary::
    :nosignatures:
    :toctree: doc/

    ~preprocessors.Concatenator
    ~preprocessors.SimpleImputer
    ~preprocessors.Chain

Categorical Encoders
--------------------

.. autosummary::
    :nosignatures:
    :toctree: doc/

    ~preprocessors.Categorizer
    ~preprocessors.LabelEncoder
    ~preprocessors.MultiHotEncoder
    ~preprocessors.OneHotEncoder
    ~preprocessors.OrdinalEncoder

Feature Scalers
---------------

.. autosummary::
    :nosignatures:
    :toctree: doc/

    ~preprocessors.MaxAbsScaler
    ~preprocessors.MinMaxScaler
    ~preprocessors.Normalizer
    ~preprocessors.PowerTransformer
    ~preprocessors.RobustScaler
    ~preprocessors.StandardScaler

K-Bins Discretizers
-------------------

.. autosummary::
    :nosignatures:
    :toctree: doc/

    ~preprocessors.CustomKBinsDiscretizer
    ~preprocessors.UniformKBinsDiscretizer

Feature Hashers and Vectorizers
-------------------------------

.. autosummary::
    :nosignatures:
    :toctree: doc/

    ~preprocessors.FeatureHasher
    ~preprocessors.CountVectorizer
    ~preprocessors.HashingVectorizer

Specialized Preprocessors
-------------------------

.. autosummary::
    :nosignatures:
    :toctree: doc/

    ~preprocessors.TorchVisionPreprocessor
