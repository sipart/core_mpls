# MPLS Core from a [EVE-NG](http://www.eve-ng.net/) virtual lab
A set of example configs for the site page: https://sipart.github.io/core_on_a_page/

* MPLS core is using ISIS as the IGP
* RSVP as the LDP
* LSPs are free running - not pre signalled
* vMX images are all QEMU Junos v14.1R10
* vMX2 is the route reflector
* NNI switches are comprised of one CumulusVX QEMU image and one Cisco IOL v15.1 image
* vSRX site routers are Junos v12.1x47-d15.4 QEMU images (running DHCP in the instance for the site PCs)
* Site PCs comprise two vPCs and two Win7 lite QEMU images
