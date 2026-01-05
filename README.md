![CPAN Version](https://img.shields.io/cpan/v/Geo-IP2Location)

Geo::IP2Location
================

This Perl module provides a fast and simple way to look up geolocation and network information for an IP address using an IP2Location BIN database.

It allows you to retrieve a wide range of data using IPv4 and IPv6 addresses, including:

 a) Geolocation: Country, Region, City, Latitude, Longitude, ZIP Code, Time Zone, District, Elevation
 b) Network: ISP, Domain Name, Connection Type, IP Address Type, Usage Type
 c) Carrier Information: Mobile Country Code (MCC), Mobile Network Code (MNC), Mobile Carrier Brand
 d) Autonomous System (AS): AS Number, AS Name, AS Domain Name, AS Usage Type, AS CIDR
 e) Additional Data: IDD Code, Area Code, Weather Station Code, Weather Station Name, IAB Advertising Category

This module can be used in many types of project such as:

 1) Selecting the geographically closest mirror for content delivery.
 2) Analyzing web server logs to determine the countries of your visitors.
 3) Detecting and preventing credit card fraud.
 4) Implementing software export controls.
 5) Displaying native languages and currencies to users.
 6) Preventing password sharing and service abuse.
 7) Geotargeting content and advertisements.

To ensure high accuracy, the commercial databases are updated on a daily, weekly or semi-monthly basis.

Commercial Databases: The complete, high-accuracy databases are available via paid subscription at https://www.ip2location.com.
Free LITE Database: A free, Creative Commons licensed database is available with sign-up at https://lite.ip2location.com.
Sample Database: A free sample DB1 database is included in the /samples directory of this distribution or can be downloaded from the IP2Location development libraries page.

## INSTALLATION

To install this module type the following:

   perl Makefile.PL
   make
   make test
   make install

## DEPENDENCIES

The complete database is available at https://www.ip2location.com under subscription package.

## IPv4 BIN vs IPv6 BIN

Use the IPv4 BIN file if you just need to query IPv4 addresses.

Use the IPv6 BIN file if you need to query BOTH IPv4 and IPv6 addresses.

## COPYRIGHT AND LICENCE

Copyright (C) 2019-2026 by IP2Location.com, support@ip2location.com

This library is released under the MIT license. See the LICENSE file for full license information.