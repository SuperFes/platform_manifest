Downloading the Source
===================

Initializing Repository
-----------------------

Repo initialization:

    $ repo init -u https://github.com/CypherOS/platform_manifest.git -b mm6.0


sync repo :

    $ repo sync

***

Building
--------

After the sync is finished, please read the [instructions from the Android site](http://s.android.com/source/building.html) on how to build.

    . build/envsetup.sh
    brunch


You can also build (and see how long it took) for specific devices like this:

    . build/envsetup.sh
    time brunch angler

Remember to `make clobber` every now and then!
