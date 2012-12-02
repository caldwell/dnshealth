# Dnshealth #

Dnshealth lets you check the serial numbers across the nameservers of your
domains. I wrote it when trying to diagnose a problem where one of my
secondary servers wasn't updating properly.

## Example ##

    $ dnshealth yingster.net
    yingster.net has 8 nameservers:
        ns1.porkrind.org serial: 1354399317
           ns0.xname.org DNS result has no information for yingster.net
           ns1.xname.org DNS result has no information for yingster.net
           ns2.xname.org DNS result has no information for yingster.net
      ns1166.dns.dyn.com serial: 1345928328
      ns2183.dns.dyn.com serial: 1345928328
      ns3130.dns.dyn.com serial: 1345928328
      ns4196.dns.dyn.com serial: 1345928328

Here's a screenshot in glorious color:

![Screenshot](dnshealth/master/screenshot.png)

The master DNS server is highlighted in white. Secondaries are cyan. Errors
are red.

## Copyright ##

Copyright (c) 2012 David Caldwell <david@porkrind.org>

## Licence ##

GPLv3. See LICENSE file for details.
