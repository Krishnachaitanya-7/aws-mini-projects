##AWS Mini Project 1 - Configuring Amazon EBS Volumes for an EC2 Instance

### objective:
	- Create a custom VPC.
	- Launch an EC2 instance in the custom VPC network.
	- create and attach an additional EBS volume to the EC2 instance.
	- Format and mount the volume to the instance.
	- Verify the volume is accessible and functional.

### Steps:
	- Create a VPC with CIDR "10.0.0.0/16".
	- Created and launched a EC2 instance in public subnet of the VPC with CIDR "10.0.0.0/20".
	- Created an additional EBS volume and attached it to the existing EC2 instance.
	- Connected to instance useing SSH protocol.
	- Formatted the volume using "mkfs -t ext4 /dev/xvdf" and mounted the the additional EBS volume using "mount".
	- Verified the new volume by creating a new directory using "mkdir".

### Output: 
	- Successful creation and attachment of the EBS volume.
	- Proper formatting and mounting of the volume.
	- Verification of volume functionality.

