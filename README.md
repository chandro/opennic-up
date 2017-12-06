# nm-opennic
**OpenNIC auto dns updater with network manager**

syntax:

./opennic.sh [*userid*] [*userkey*]

Replaces the Network Manager dns servers with the 3 most responsive OpenNIC dns servers for your location. resolv.conf is alo updated for immediate implementation of the new dns entries.

*userid* and *userkey* are optional, they correspond to the member's *user* and *auth* and are used to register one's IP for whitelisting.
