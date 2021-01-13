# Bath Historical Images

This repository contains metadata and links to historical images for Bath 
and the surrounding area.

## What's Included?

The data is provided for anyone interested in local history who would like 
openly licensed images to use in their research, publications or applications.

In comparison to official archives the collection is clearly very small. If 
you want to do serious historical research then you will need to consult other 
resources. However few of those resources are available under open or 
liberal licences that allow them to be reused. If you need something for 
reuse then this is a good starting point.

The list includes images of paintings, drawings, photographs and scans from out 
of copyright books that depict Bath and its surrounding areas.

Some of these images include historical maps that might be reused for other purposes.

## Sources

The data was manually collected by searching the following websites 
and collections:

* [British Library](https://www.flickr.com/photos/britishlibrary/) collection on Flickr
* [British Museum](https://www.britishmuseum.org/collection)
* [Yale Centre for British Art](http://collections.britishart.yale.edu/)
* [Library of Congress Prints and Photographs](https://www.loc.gov/pictures)
* [Wellcome Collection](https://wellcomecollection.org/)
* [Old Book Illustrations](oldbookillustrations.com)
* [Wikimedia](https://commons.wikimedia.org/wiki/Main_Page)
* [Smithsonian](https://www.si.edu/search/collection-images)
* [Internet Archive](https://archive.org)

As the data was manually compiled, there may be errors or ommisions. If you spot 
something then [email me](mailto:leigh@ldodds.com).

If you know of other public domain or openly licensed collections then also 
get in touch. And, if you want help releasing metadata about other collections, 
especially if they can be openly licensed, then let me know as I may be able to help!

## Schema

* Source - collection in which the image is listed 
* Type - type of resource
* Title - title of the image, generally from the catalogue entry but in a few cases this has been replaced with a label that is clearly visible on the image
* Date - date of publication (see below)
* Creator - the artist or photographer who created the image, where known
* Id - a unique identifier for the image where available. This is usually the catalogue or accession number from the relevant collection
* Homepage - a link to the catalogue entry describing the image
* Media Link - a direct link to the image 
* Map - Y/N to indicate whether the image depicts a map of a building, the city or local area
* Licence - the licence for the image. Most are public domain, some are only available under a non-commercial licence
* Longitude - longitude (see below)
* Latitude - latitude (see below)
* Notes - additional notes or comments

## Dates

Some notes on date formats in the date column:

* basically ISO 8601 (yyyy-mm-dd or yyyy-mm or yyyy) depending on detail available
* sometimes only year range is available: `1780-1790`
* sometimes only a starting year is available (e.g. after 1780): `1780+`
* sometimes there's a choice of year: `1778/17791`
* sometimes there's just a centry, e.g `c19th century`
* empty if date is unknown

## Media Links

In some cases there are multiple versions available, ranging from low quality 
thumbnails through to very high resolution scans. In some cases there are 
TIFF as well as JPG formats.

In general, I have provided a link to the highest resolution version of the JPG 
image available in the collection. Except for Flickr where I have just linked to the 
Large format (not Original).

This is to give a reasonably clear high-res image for viewing online. If you want 
the highest resolution possible then check the individual catalogue entry.

## Geocoding

This is still a work in progress.

For each of the images I am aiming to provide a latitude/longitude that will 
help to place the image on a map.

My approach is to gecoode the images as if they had been taken using a modern 
mobile phone camera. So, for example if the image is of the Abbey then the 
coordinates are those of the abbey, its the position of wherever the artist or 
photographer was standing when they took the image. 

I also plan to add a direction indicator using points of the compass.

I have already separately georeferenced the majority of the maps and plan to 
release those as separately geocooded images that can be easily imported into 
tools like QGIS.

## Data Licence

The images are all either public domain, openly licensed or available for 
non-commercial use. Details of the licence for each image is included the 
metadata.

The metadata is in the public domain, via a [CC0](https://creativecommons.org/publicdomain/zero/1.0/deed.en) waiver. So you may use this information however you like, but will need to 
respect the licences associated with the individual images.


