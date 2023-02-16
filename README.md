# Wordpress_AWS
Host a single instance website on AWS cloud<br/>

Things to do:<br/>
1)Create an IAM user.<br/>
2)Create a S3 bucket.<br/>
3)Create a VPC. Before creating a VPC, you need to select a region by considering factors such as cost. Create 2 subnets inside VPC, a public and private.<br/>
4)The public subnet hosts your web application for that for which we need an EC2 instance.<br/>
5)The private subnet deploys your RDS and MySQL databases.<br/>
6)Setup connection between RDS and EC2 instance.<br/>
7)Install Wordpress website on the instance.<br/>
8)Start hosting a wordpress website on the EC2 instance. <br/>
9)Export the static assets into the S3 bucket.<br/>
