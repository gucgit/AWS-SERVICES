# AWS-SERVICES
VPC......
Amazon Virtual Private Cloud (Amazon VPC) enables you to launch AWS resources into a virtual network that you've defined. This virtual network closely resembles a traditional network that you'd operate in your own data center, with the benefits of using the scalable infrastructure of AWS.
#vpc parameters 
subnets
route table 
internet gate way 
security groups 
# vpc peering process
establishing connection between two or more  private networks i.e may be in same zones or different az's 
the process of vpc peering is intially have to make peer connection in vpc section and add routing with subnets and make request from one vpc to another vpc 
Modify my route tables now to go directly to the route tables page, or choose Close to do this later.
or.....
Choose Create peering connection.

Configure the following information, and choose Create Peering Connection when you are done:

Peering connection name tag: You can optionally name your VPC peering connection. Doing so creates a tag with a key of Name and a value that you specify.

VPC (Requester): Select the requester VPC in your account with which to request the VPC peering connection.

Account: Ensure My account is selected.

Region: Choose Another region, select the Region in which the accepter VPC resides.

VPC (Accepter): Enter the ID of the accepter VPC.

In the confirmation dialog box, choose OK.

In the Region selector, select the Region of the accepter VPC.

In the navigation pane, choose Peering Connections. Select the VPC peering connection that you've created, and choose Actions, Accept Request.

In the confirmation dialog, choose Yes, Accept. A second confirmation dialog displays; choose Modify my route tables now to go directly to the route tables page, or choose Close to do this later.

Create with VPCs in different accoun
