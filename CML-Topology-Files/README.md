# LISP VXLAN Labs

These topology files and configs are part of the LISP/VXLAN Basic Workbook available on Leanpub, copyright 2020 Tim McConnaughy.

Here contains the lab topoloies with initial configurations for Cisco Modeling Labs (CML).

## Disclaimer
Currently the topology and startup configs for Labs 1-3 in the Basic workbook, and Labs 6-7 in the Expanded workbook have been uploaded, but are not yet verified.  Before starting the lab you should verify the configuration against the configurations provided by Tim, and verify interfaces are in the proper state.  If you find any errors please let me know and I will update the configs.

## Environment:
The following software versions were used to build these topologies
 - CML Version 2.1.0-b17
 - CSR1000v 17.03.01a (6 nodes)
 - IOSv 15.9(3) (5 nodes)
 - Desktop - Alpine 3.12 XFCE (4 nodes)
 - Server - Tiny Core Linux 8.2.1 (1 node)
 

## Changes
There are a few changes to Tim's initial configurations as follows:
 - CSR1000v in CML do not support sub interfaces, as such, labs that require subinterfaces on the CSR's have been changed to use Bridge Domain Interfaces instead.
 - Routers that do not require LISP configuration have been replaced with IOSv instead of CSR1000v, this reduces the CPU/RAM requirements to run the lab

## Links
 - https://leanpub.com/u/tmcconnaughy
 - https://github.com/jgolbez/lispvxlanbasicwb
 - https://github.com/jgolbez/lispvxlanexpandedwb

