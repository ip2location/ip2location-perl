Geo::IP2Location
================

This Perl module provides fast lookup of country, region, city, latitude, longitude, ZIP code, time zone, ISP, domain name, connection type, IDD code, area code, weather station code and station, MCC, MNC, mobile carrier brand, elevation and usage type from IP address using IP2Location database. This module uses a file based BIN database available at https://www.ip2location.com/database/ip2location upon subscription. You can visit https://www.ip2location.com/development-libraries to download BIN sample files. This database consists of IP address as keys and other information as values. It supports all IP addresses in IPv4 and IPv6.

This module can be used in many types of project such as:

 1) select the geographically closest mirror
 2) analyze web server logs to determine the countries of visitors
 3) credit card fraud detection
 4) software export controls
 5) display native language and currency
 6) prevent password sharing and abuse of service
 7) geotargeting in advertisement

The database will be updated in monthly basis for the greater accuracy. Free sample DB1 database is available at /samples directory or download it online from https://www.ip2location.com/development-libraries.

The complete database is available at https://www.ip2location.com under paid subscription. Meanwhile, free creative-common database is also available at http://lite.ip2location.com upon sign-up.


## INSTALLATION

To install this module type the following:

   perl Makefile.PL
   make
   make test
   make install

## DEPENDENCIES (IP2LOCATION BIN DATA FILE)

This library requires IP2Location BIN data file to function. You may download the BIN data file at

* IP2Location LITE BIN Data (Free): https://lite.ip2location.com
* IP2Location Commercial BIN Data (Comprehensive): https://www.ip2location.com


## IPv4 BIN vs IPv6 BIN

Use the IPv4 BIN file if you just need to query IPv4 addresses.

Use the IPv6 BIN file if you need to query BOTH IPv4 and IPv6 addresses.


## COPYRIGHT AND LICENCE

Copyright (C) 2019 by IP2Location.com

This library is licensed under LGPLv3; you can redistribute it and/or modify it under the same terms as Perl itself, either Perl version 5.8.6 or, at your option, any later version of Perl 5 you may have available.
