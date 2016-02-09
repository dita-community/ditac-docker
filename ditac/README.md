Out of the Box XMLmind DITA Converter Container
===============================================

This container provides an image
of the XMLmind DITA Converter as 
distributed by the XML Mind.

It defines one volume in addition to the
two volumes defined by the dita-ot-base
container:

- /opt/ditac/ditac is the full ditac installation.

NOTE: Use the image ditac/ditac-base as the extension base for new ditac images.
This image will not work because the volume definitions in this image prevent other images
based on it from persisting anything to the ditac directory. 