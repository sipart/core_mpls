# core_mpls
## A set of example configs for the site page: https://sipart.github.io/core_on_a_page/

* The core is using ISIS as the IGP. RSVP as the LDP
* The LSPs are free running - NOT pre signalled
* vMX images are all QEMU Junos v14.1R10
* vMX2 is the route reflector
* The NNI switches are comprised of one CumulusVX QEMU image and one Cisco IOL v15.1 image
* The vSRX site routers are Junos v12.1x47-d15.4 (running DHCP for the site PCs)
* Site PCs comprise two vPCs and two Win7 lite QEMU images
