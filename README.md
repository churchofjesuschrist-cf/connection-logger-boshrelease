connection-logger-boshrelease
=============================

This release supplies a `connection-logger` job, to be deployed on Diego cell vm's.
It installs [ulogd](https://www.netfilter.org/projects/ulogd/) on the cell, and hooks
into iptables, providing diagnostic information via dropsonde directly into
application logs. This offers application developers valuable diagnostic information
when their applications fail to connect on the network.
