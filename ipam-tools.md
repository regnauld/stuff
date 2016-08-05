# IPAM and CMDB software

## IPAM

* HaCi http://haci.larsux.de/ - 2015-03

    - IPAM only, v4/v6, multiple POPs, uses templates, space visualization

* GestioIP  http://haci.larsux.de/ - 2016-02

    - IPAM w/ VLAN management, subnet disco. via SNMP, space visualization
    - BIND zone file gnerator fwd/ptr
    - Integration OCS Inventory NG

* TeemIP - http://www.combodo.com/teemip-194 (2015-03), part of iTop or alone

    - request management w/portal systen for requestors
    - DNS
    - extensible

* Subnetsmgt http://sourceforge.net/projects/subnetsmngr/ - 2013-05

    - IPAM
    - PowerDNS integration

* phpIPAM - http://phpipam.net - 2016-02

    VLAN, VRF, visualization, RIPE, host scanning, etc...
    IP request form

* netmagis - http://netmagis.org - 2015-09

    Split DNS support
    DHCP/DNS integration
    VLAN maanagement
    Generate traffic graphs

## Inventory management / CMDB (possibly including IPAM)

* iTop https://wiki.openitop.org/doku.php - 2014 (w/updates 2016)

    - Modular CMDB
    - Modules like TeemIP

* Netdot - https://osl.uoregon.edu/redmine/projects/netdot - 2015-01

    - great for campus networks
	- no overlapping IP/VLAN support - yet!
	- no VRF support
	- great integration to third party tools
	- actively maintained

* Racktables - http://racktables.org/ - 2016-02 - active

    - Rack/DC specific (objects / IP / vlan / asset tags)
    - no built-in DNS integration

* glpi - http://www.glpi-project.org - 2016-04 - active

    - Full fledged asset/inventory management
    - Modular, including Puppet integration
    - ITILish

* OCS inventory-ng

    - Inventory / deployment
    - Integrates with GLPI
    - Lots of typos on website...
    - Download requires filling out a form, but it's on github

* Ralph 3 - http://allegro.tech/ralph/ - 2016 - active

    - rack/asset mgmt
    - rack visualization
    - review http://blog.admin-linux.org/pilotage/ralph-systeme-de-gestion-d-actifs-pour-datacenter-cmdb-dcim

* OpenDCIM - http://www.opendcim.org/ - 

    - DC physical inventory
    - multi site support
    - calculate center of gravity for rack (!)
    - PDU integration

* opennetadmin http://opennetadmin.com - 2016-03 - active

	- modular
	- support for hooks/host actions
	- config. backup
	- VLAN, etc.
	- CLI for interacting with system
	- DNS view support

* netbox https://github.com/digitalocean/netbox - 2016-06 - active

	- new project from DigitalOcean

* nocproject - https://kb.nocproject.org/display/SITE/NOC - 2015-05 / active

    - this thing is in another class - it does *everything*,
      from configuration management to outage planning to
      inventory, provisioning, etc... 50 vendors+ supported
    - around for some years, written by Russians with
      some documentation in English, and even more in Russian
    - 120 people on the Telegram chat room!

    - for the new version, they built a deployment system called
      "Tower" just to manage Noc installations, based around ansible:

    https://bitbucket.org/nocproject/noc-tower

* cmbuild http://www.cmdbuild.org/en/prodotti/cmdbuild - 2016-06 / active

    - this is a toolkit for building your own ITIL compliant
      CMDB
    - probably overkill for anyone

Others:

* tipp - https://github.com/tobez/tipp - 2014

    - IPAM and only IPAM 
    - In production for some years

* ipplan (iptrack) http://iptrack.sourceforge.net/ - 2010

    - dead ?
    - v6 support added later
