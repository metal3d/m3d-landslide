m3d-landslide
=============

Landslide theme that append a nice "3D coverflow like"


How to use ?
------------

Create your slide as mentionned on landslide documentation. See https://github.com/adamzap/landslide
Get this theme in a standard directory then use:

    landslide your_file.rst -t path/to/theme/m3d-landslide

You can put this theme in the standard theme directory, to get this path, type in terminal:

    python -c 'import os,landslide; print os.path.join(landslide.__path__[0],"theme")'

eg. /usr/lib/python2.7/site-packages/landslide/themes/ (this path can be different in you system). 

You can install (as root) like this:

    cd $(python -c 'import os , landslide; print os.path.join(landslide.__path__[0],"theme")') && git clone git://github.com/metal3d/m3d-landslide.git m3d

After this installation, you can use theme as this:

    landslide your_file.rst -t m3d

To be up-to-date, run this command:

    #this command go to "m3d" theme path and runs git update. "cd -" get you back to you last directory
    cd $(python -c 'import os , landslide; print os.path.join(landslide.__path__[0],"theme","m3d")') && git update ; cd -

Don't forget to help me by forking this repository and give some pull-request :)


