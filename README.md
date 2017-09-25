Spicy Vanilla
=====================

Getting Started
---------------

To build SpiceyVanilla from source, you'll need to be familiar with Git and Repo ( duh... )


Initialize your local repository by running this command:

	repo init -u https://github.com/SpicyVanilla/manifest.git -b oreo

Sync source with this command:

	repo sync

After syncing is done, use these commands to build:

    1.) . build/envsetup.sh
    2.) brunch xxxx yyyy
    
    xxxx= device name ( eg. bullhead )
    yyyy= build type ( user, userdebug, eng )

    >>--> If you don't specify a build type, then "user" is default
