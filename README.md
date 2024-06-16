# 2 MSPS demodulator for testing


# dump1090-mutability Debian/Raspbian packages

This version is licensed under the GPL (v2 or later).
See the file COPYING for details.

# Features

* 2.4MHz "oversampling" support
* doesn't run as root
* supports FlightAware-TSV-format connections directly (same as the FlightAware version - no faup1090 needed)
* can start from init.d, with detailed config via debconf or `/etc/default/dump1090-mutability`
* can serve the virtual radar map via an external webserver (lighttpd integration included by default)
* map view uses receiver lat/long given to dump1090 automatically
* somewhat cleaned-up network code
* tries to do things "the debian way" when it comes to config, package structure, etc
