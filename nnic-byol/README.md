GCP BIG-IP 8-NIC VIA-API BYOL
=============================

The presented GCP template is created to support a BIG-IP HA setup where each BIG-IP is equiped with 8-NICs.
High Availibility of the BIG-IP cluster is delivered through an active/standby setup, where one BIG-IP will act as the active instance and the other BIG-IP instance will be standby. HA provides netwerk failover by using F5 Cloud Failover Extension.

This template are modified from this original source: https://github.com/F5Networks/f5-google-gdm-templates/tree/master/supported/failover/same-net/via-api/3nic/existing-stack/byol

How to use
==========

Clone this repo to your local site and make sure to keep all files in one directory to make the template function correctly.
Before filling in the .yaml, be sure to:
- Create VPC's and Subnets
- Create a service account with the right authorization. (https://clouddocs.f5.com/products/extensions/f5-cloud-failover/latest/userguide/gcp.html#create-and-assign-an-iam-role)
- Two BIG-IP licenses

Disclaimer
==========

Everything shown, explained and written is done with the best intentions and can be leveraged at you own risk.

All content included in this repository is not supported by F5.
