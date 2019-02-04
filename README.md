# Set-up-MySQL-master-slave-replication
Master-slave data replication allows for replicated data to be copied to multiple computers for backup and analysis by multiple parties.
Needed changes identified by a group member must to be submitted to the designated “master” of the node.
This differs from Master-Master replication, in which data can be updated by any authorized contributor of the group.
This article provides steps for setting up MySQL master-slave database replication between two Cloud Servers.
The operating system used for the examples in the article is CentOS 6, built from a Rackspace Cloud Servers base image.
