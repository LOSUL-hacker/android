LineageOS Ultra Legacy (merged with upstream by me)
===========

Getting started
---------------

To get started with Android/LineageOS, you'll need to get familiar with [Source Control Tools](https://source.android.com/setup/develop).

To initialize your local repository using the LineageOS trees, use a command like this:
```
repo init -u https://github.com/LOSUL-hacker/android.git -b lineage-20.0 --git-lfs
```
Then to sync up:
```
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```
Please see the [LineageOS Wiki](https://wiki.lineageos.org/) for building instructions, by device.


Submitting patches
------------------
Patches are always welcome! Please submit your patches via pull request!

Buildbot
--------

All supported devices are built weekly and periodically as changes are committed to ensure the source trees remain buildable.

You can view the current build statuses at [LineageOS Buildkite](https://buildkite.com/lineageos).

Builds produced weekly by the buildbot can be downloaded from [LineageOS downloads](https://download.lineageos.org/).

