# Network ACL rules for a Private Subnet in an AWS VPC

## Inbound rules

1. This rule allows the Public subnet to make a request to the database in the Private Subnet.

2. This allows changes to the database originating from the connected application, sent through the Public subnet.

3. This is to allow the use of an SSH key when using a virtual machine.

## Outbound rules

1. This allows the database to query for software updates.
