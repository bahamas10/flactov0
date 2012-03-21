Flac to V0
==========

Flac to mp3 v0 converter script

This script was created to make it easy to convert flac files
to mp3 v0 files over the command line.  Its usage mimics that of
cp, by allow 1 or many source files, and a destination.

Usage
=====

    Usage: flactov0 SOURCE DEST
    Usage: flactov0 SOURCE... DIRECTORY

    Source is a flac file and dest is the destination
    file or folder.

    Source can be 1 or more flac files, if multiple
    sources are present the final argument must
    be the destination directory.

Examples
========

    ~$ flactov0 mysong.mp3 mysong.flac
    ~$ flactov0 *.mp3 folder_for_flac/
