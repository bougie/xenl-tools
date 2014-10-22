xenl-tools
=========


About
-----

xenl-tools contains a collection of python scripts for working with Xen
guest images under [Debian](http://www.debian.org/).

xenl-tools currently has scripts to install releases of debian.

### Debian

* Jessie 8


Requirements
------------

To use these tools you'll need the following software:

* [debootstrap](http://packages.debian.org/debootstrap)
* [Python 3](https://packages.debian.org/jessie/python3)


Installation
------------

As root or with sudo, clone the repository and copy xen-tools.conf.sample to
**/etc/xenl-tools/xen-tools.conf**.


The Scripts
-----------

Here is a brief description of each included script

### xl-create-image

This script is designed to create new images which may be used
with the Xen hypervisor.

### xl-debootstrap2tar

This script is designed to create a tarball from a debootstrap which
may be used by xt-create-image. After, the tarball can be manually
personalized to include for exemple a new embded software.
Also, using a tarball do the install process very faster
