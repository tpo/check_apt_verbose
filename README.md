check_apt_verbose
=================

A check for Nagios/Icinga that reports back on upgradeable packages.

It is a trivial wrapper around the standard check_apt command, that outputs also a long_output in the right place, so that the admin can see which package upgrades are pending.

Made for Sourcepole.com by Tomáš Pospíšek <tpo_deb@sourcepole.ch>
