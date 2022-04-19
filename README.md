# WEB-STACK-IMPLEMENTATION-LEMP-STACK-

This is a project which implement the use of Web Stack (LEMP STACK) In AWS

## CREATING EC2 INSTANCE ON AWS

- Select region (the cl and launch a new EC2 instance of t2.micro family with Ubuntu Server 20.04 LTS (HVM)

- Create a pair Key as the EC2 is created

- Move into the folder where the pair key is downloaded and run the following command to connect to the instance 
             
             - sudo chmod 0400 <private-key-name>.pem
              
             - ssh -i <private-key-name>.pem ubuntu@<Public-IP-address>
              
            
## INSTALLING THE NGINX WEB SERVER
- we update the server package index with the command
             sudo apt update
