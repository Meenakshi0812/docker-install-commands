connect EC2 instance in AWS
Create a security group that can allow all IP to all ports. Create inbound and outbound both.
•	Launch an EC2 instance with AWS Linux 2 and create key pair in ppk format
•	We are going to use Putty to connect our instances. You can use any SSH client to connect.
•	to connect any instance you need to provide
o	IP
o	Username
o	Password/private key
o	Port (SSH by default takes port number 22)
Install Docker in AWS Linux 2
•	Update OS packages
sudo yum update -y
•	Install Docker
sudo amazon-linux-extras install docker or sudo yum install docker
•	Start Docker
sudo service docker start
•	Enable it
sudo systemctl enable docker
•	Add user to docker group
sudo usermod -a -G docker ec2-user
Just logout and login again to run docker commands with normal user.







