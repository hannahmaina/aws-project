# aws-project
Deploying a Node Js Application on AWS EC2
In this project I will Deploy my application my First App to AWS and expose it to other user

#1. Testing the project locally
   Clone this project https://github.com/hannahmaina/aws-project.git 

##2. Set up the environment variables for this application - (.env) 
         
         create a file for this env variable) (for saving our credentials)
DOMAIN= ""
PORT=3000
STATIC_DIR="./client"

PUBLISHABLE_KEY=""
SECRET_KEY=""

###3. Initialise and start the project
 
npm install
npm run start

#A. Set up an AWS EC2 instance

Create an IAM user & login to your AWS Console
Access Type - Password
Permissions - Admin
Create an EC2 instance
Select an OS image - Ubuntu
Create a new key pair & download .pem file

##B. Connect to instance ussing ssh 
ssh -i instance.pem ubunutu@<IP_ADDRESS> 

###C. Configuring Ubuntu on remote VM

  Deploying the project on AWS
  


Instance type - t2.micro
Connecting to the instance using ssh
