ocf_debug
=========

This script generates the needed exports to debug a resource in pacemaker on the commandline.

Example
=======

	root@alice:~ # ocf_debug p_ip_db1 
	Please run the following command by yourself

	Generating exports for "p_ip_db1":
	export OCF_RESKEY_ip="192.168.1.100"
	export OCF_RESKEY_cidr_netmask="24"
	export OCF_ROOT=/usr/lib/ocf

	Runit with:
	/usr/lib/ocf/resource.d/heartbeat/IPaddr2
