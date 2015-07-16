FUSION ROM !!
=============

Support Fusion rom
------------------
Follow the Fusion rom builds. Please visit and support our efforts

[Fusion Website] (http://www.fusion-rom.net)

Getting Started
---------------

To get started with building Fusion rom, you'll need to get
familiar with [Git and Repo](http://source.android.com/download/using-repo).
Contact us for permission to access the private repositories.

Then to initialize your local repository using the Fusion rom trees, use this command:

    repo init -u git://github.com/Fusion-Rom/fusion_manifest.git -b lp5.1

Then to sync up:

    repo sync

Then to build:

    . build/envsetup.sh

    lunch

    make -j16 fusionsp (Or simply run ./build-fusion.sh)


You can speed up subsequent builds by adding this command in terminal:

export USE_CCACHE=1

