# Lacework FortiCNAPP AWS SCP Example

# Purpose
This project is an example AWS Service Control Policy (SCP) to allow Lacework to analyze resources in an AWS organisation.

# How it works
To allow Lacework to analyze resources in an AWS organisation, we need to add 'ArnNotLike' to the SCP to prevent Lacework from being denied access to the resources.

# SCP in AWS

SCP is set at the root of the organisation, in the AWS Management Account. To allow Lacework to analyze resources in an AWS organisation, we need to add an 'ArnNotLike' exception to an SCP 'Deny' statement.




