# cloudformation-cross-stack-reference
These two templates are used for cross stack.
Network-template.yaml contains the VPC resources and the cross-stack-template.yaml contains the EC2 resource.
Usage:
You launch the network-template.yaml to provision the VPC first
Then you launch cross-stack-template.yaml to spin up the EC2 in the VPC.