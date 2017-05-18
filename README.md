What Is Here
------------

This project consists of two scripts:
* dback: for backing up computers using the OSX operating system.
* dbackL: for backing up computers using a Linux operating system.

Why Bother?
----------

There exist similar projects rsnapshot, Back In Time, and more. I wrote these scripts because I wanted the following features:
* Incremental backup using hard linked files (--link-dest feature of rsync).
* Complete logging of the backup operation, to a simple text file.
* No automatic deletion of old backup sets.
* Backup set names derived from date/time (like Apple's Time Machine).
* Dead simple (one script file only).

Getting Started
---------------

Copy dback or dbackL somewhere convenient. Assuming the script is in your path, issue the command

$ dback userguide | less

or

$dbackL userguide | less
