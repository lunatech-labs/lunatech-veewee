Lunatech Veewee Configuration
=============================

Lunatech uses veewee to build baseboxes to be used with Vagrant. In this repository, we keep our _definitions_.

Baseboxes
=========

We currently have two basebox definition, for an Ubuntu 10.04.4 server and for an Ubuntu 12.04.1 server. These are both LTS releases. We only use Chef, so Puppet installation has been omitted.

Usage
=====

Install veewee, and then run "vagrant basebox build 'ubuntu-10.04.4-server-amd64'" to build the basebox, and follow the instructions.

Problems?
=========

If you get the error 'we tried to create a box or a box was here before', then you may need to manually remove an older residual VM from /Users/me/Virtualbox Vms
