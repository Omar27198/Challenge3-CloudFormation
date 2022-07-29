# Challenge3-CloudFormation {Servers and Security Groups}
Project Overview<br />
You have been tasked with creating the required Infrastructure-as-code scripts for a new cloud environment in AWS. The Lead Solutions Architect for the project sends you the following diagram.<br />

![AWSWebApp](https://user-images.githubusercontent.com/23401470/181836710-4a64fe13-ec34-4035-bc4d-5dc944e90f3d.jpeg)

ToDo<br />
Write a CloudFormation script that:<br />
1-) SecurityGroup: A security group for the server, that allows inbound port 80 access, for future use.<br />
2-) Auto Scaling Group: with InstanceType: t3.medium and MinSize: '3' MaxSize: '5'<br />
3-) Elastic Load Balancing<br />
4-) Bonus/Optional: Instead of hard-coding the VPC and Subnet ID, use the import-export feature to cross reference the resources created in Challenge 2.<br />
