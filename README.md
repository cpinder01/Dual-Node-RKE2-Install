## Dual-Node-RKE2-Install

This repository uses ansible to create a dual node RKE2 cluster with 2 master nodes.

# Where to run

This needs to run on one of the nodes that you intend to use for your RKE2 cluster

# What to change

To use this script, change the hosts_k8s.ini file to include the IP address and user profile of your second node. Also, to make sure the second node can join correctly, change the IP address within the 'Copy content into file' task in the sonfigure-second-node role to the IP address of the node you are running the script from.

This script is a work in progress and will be updated.
