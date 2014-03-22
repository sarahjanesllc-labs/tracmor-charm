# Overview

Tracmor is the commercial open source solution that makes it easy to
centralize and track your assets online. From its simple web-based
interface to its intuitive workflow, Tracmor will help you drive down
costs while maintaining an accurate record of your assets.

Usage
-----

Step by step instructions on using the charm:

    juju deploy mysql
    juju deploy tracmor
    juju add-relation mysql tracmor
    juju expose tracmor

You can then browse to http://ip-address to configure the service.

Configuration
-------------

N/A

Contact Information
-------------------

Author: Adam Stokes
Report bugs at: https://github.com/ajscg/tracmor-charm/issues
Location: http://jujucharms.com/charms/precise/tracmor
