# Eye-Fi Tools #

This project is comprised of two subprojects; the projects are intended to faciliate the use of any [Eye-Fi][1] cards
that have been _intentionally_ disabled by the manufacturer.


## eyefi-config ##

This is a text-based utility that allows control of the settings of an [Eye-Fi][1] card.


### Supported Platforms ###

As of the current version, **eyefi-config** supports the following platforms:
- Linux
- FreeBSD
- Mac OS X


## eyefiserver2 ##

This is a _re-implementation_ of the **Eye-Fi Center** software, which provides an **HTTP** server on the **LAN** for
any cards to upload their images to.

It has been coded in [Python][2] **2.7** -- one major task is improving it to **Python 3.x**.




[1]:	<http://eye.fi>
[2]:	<https://python.org>
