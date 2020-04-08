``contextily``: context geo tiles in Python
-------------------------------------------

``contextily`` is a small Python 3 package to retrieve and write to disk
tile maps from the internet into geospatial raster files. Bounding boxes
can be passed in both WGS84 (``EPSG:4326``) and Spheric Mercator
(``EPSG:3857``). See the notebook ``contextily_guide.ipynb`` for usage.

|Build Status| |Coverage Status|

.. figure:: tiles.png
   :alt: Tiles

   Tiles

-  Toner and Terrain map tiles by Stamen Design, under CC BY 3.0. Data
   by OpenStreetMap, under ODbL.
-  Watercolor map tiles by Stamen Design, under CC BY 3.0. Data by
   OpenStreetMap, under CC BY SA.

Dependencies
------------

-  ``mercantile``
-  ``numpy``
-  ``matplotlib``
-  ``pillow``
-  ``rasterio``
-  ``requests``
-  ``geopy``
-  ``joblib``

Installation
------------

**Python 3 only**

`Latest released
version <https://github.com/darribas/contextily/releases/tag/v0.99.0>`__:

.. code:: sh

   pip3 install contextily # installs the latest released version (v0.99.0)

Latest `release
candidate <https://github.com/darribas/contextily/releases/tag/v1.0rc2>`__
(includes functionality such as ``add_basemap`` coming in version 1.0:

.. code:: sh

   pip3 install contextily==1.0rc2 # installs the latest release candidate (v1.0rc2) 

Contributors
------------

-  `Dani Arribas-Bel <http://darribas.org/>`__
   (```@darribas`` <http://twitter.com/darribas>`__)
-  `Joris Van den Bossche <https://jorisvandenbossche.github.io/>`__
   ```@jorisvandenbossche`` <https://twitter.com/jorisvdbossche>`__)
-  `Levi Wolf <http://ljwolf.org/>`__
   (```@levijohnwolf`` <https://twitter.com/levijohnwolf>`__)
-  `Chris Holdgraf <http://chrisholdgraf.com/>`__
   (```@choldgraf`` <http://twitter.com/choldgraf>`__)
-  `Filipe
   Fernandes <https://ocefpaf.github.io/python4oceanographers/>`__
   ([@ocefpaf](http://twitter.com/ocefpaf))

License
-------

BSD compatible. See ``LICENSE.txt``

.. |Build Status| image:: https://travis-ci.org/darribas/contextily.svg?branch=master
   :target: https://travis-ci.org/darribas/contextily
.. |Coverage Status| image:: https://coveralls.io/repos/github/darribas/contextily/badge.svg?branch=master
   :target: https://coveralls.io/github/darribas/contextily?branch=master
