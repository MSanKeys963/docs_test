===================
Zarr Specifications
===================

.. toctree::
   :maxdepth: 1
   :hidden:
   :caption: v3

   Core <specs/v3/core/v3.0>
   specs/v3/data-types
   specs/v3/codecs
   specs/v3/stores
   specs/v3/array-storage-transformers

.. toctree::
   :maxdepth: 1
   :hidden:
   :caption: v2

   Zarr spec v2 <specs/v2/v2.0.rst>

.. toctree::
   :maxdepth: 1
   :hidden:
   :caption: v1

   Zarr spec v1 <specs/v1/v1.0.rst>

Zarr Specification refers to a specification for a chunked, compressed, N-dimensional array format primarily designed for storing large numerical arrays efficiently. It is commonly used in scientific computing and data analysis.

The Zarr format offers benefits such as efficient use of storage, parallel and out-of-core processing capabilities, and compatibility with various scientific computing libraries such as NumPy, Dask, and Xarray.

The specification defines how data should be organized within a Zarr store, including details on chunking, compression, metadata, and other attributes necessary for efficient storage and retrieval of array data. This specification helps ensure interoperability between different software implementations that support the Zarr format.

Contributing 🤝🏻
~~~~~~~~~~~~~~~

If you wish to contribute to Zarr’s codebase, propose a new ZEP(s),
website, blog posts or in any way, please visit Zarr’s GitHub
`here <https://github.com/zarr-developers/>`__. You can discuss the
change you want to see by opening an issue in the appropriate
repository, or if the issue is already present, feel free to submit a
pull request.