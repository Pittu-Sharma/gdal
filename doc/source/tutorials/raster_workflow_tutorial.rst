Raster Processing Workflow Tutorial
===================================

This tutorial demonstrates a simple GDAL workflow for raster processing.

Convert a raster dataset
------------------------

The following command converts a raster dataset to GeoTIFF format.

.. code-block:: console

   gdal_translate input.tif output.tif

Reproject the raster
--------------------

The following command reprojects the raster dataset to EPSG:4326.

.. code-block:: console

   gdalwarp -t_srs EPSG:4326 input.tif reprojected.tif

This workflow demonstrates a basic conversion and reprojection
process using GDAL command line tools.
