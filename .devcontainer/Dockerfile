FROM ubuntu:22.04
# minimal docker file to get sp and sf running on ubunty 16.04 image,
# using gdal/geos/proj from ppa:ubuntugis/ubuntugis-unstable

RUN apt-get update && apt-get install -y software-properties-common dirmngr
RUN add-apt-repository ppa:ubuntugis/ubuntugis-unstable
