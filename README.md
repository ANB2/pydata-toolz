PyToolz Tutorial for PyData 2013 - NYC
======================================

Requirements
------------

    Python 2.6, 2.7, 3.2, 3.3

    pip install toolz

Data
----

Data for most of the notebooks resides in the `data` directory

Those interested in the human genome can find it at
http://hgdownload.cse.ucsc.edu/goldenPath/hg19/chromosomes/

Those interested in the Github data can find it at
http://www.githubarchive.org/


Errata
------

After the talk Jake Vanderplas showed me that indeed `numpy` does support
accumulation on any binary operator.  Try the following in `ipython` for a
list of supported binops

    import numpy
    numpy.*.accumulate?
