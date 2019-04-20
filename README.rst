Tadpoles.com Scraper
==============================

WHAT
++++

Tadpoles.com is a site where daycare centers sometimes post 
pics of kids if they use the tadpoles ipad app. They don't support
bulk downloads though...until now. 

Dependencies
+++++++++++++

* Docker

Usage
+++++

To use it::

    $ ./scripts/build.sh
    $ ./scripts/run.sh

The images get saved to ./img/ in year/month subdirectories.

Note: That videos are also downloaded but must be renamted .mp4 to view them again. 
