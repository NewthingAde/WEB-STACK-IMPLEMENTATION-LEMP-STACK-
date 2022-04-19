# WEB-STACK-IMPLEMENTATION-LEMP-STACK-

This is a project which implement the use of Web Stack (LEMP STACK) In AWS

## CREATING EC2 INSTANCE ON AWS

- Select region (the cl and launch a new EC2 instance of t2.micro family with Ubuntu Server 20.04 LTS (HVM)

- Create a pair Key as the EC2 is created

- Move into the folder where the pair key is downloaded and run the following command to first change the mode
             
             - sudo chmod 0400 <private-key-name>.pem
             
- Use the command to connect to the instances
              
             - ssh -i <private-key-name>.pem ubuntu@<Public-IP-address>
              
            
## INSTALLING THE NGINX WEB SERVER
- we update the server package index with the command
            
            - `sudo apt update´

- we use the command to then get NGINX installed

            - `sudo apt install nginx`

- To verify that nginx was successfully installed and is running as a service in Ubuntu, run:
          
            - ´sudo systemctl status nginx´

- we try to access it locally on our ubuntu shell

            - `curl http://localhost:80´
     
                        or use 
                        
              `curl http://127.0.0.1:80´           
         
<img width="813" alt="ngix" src="https://user-images.githubusercontent.com/80678596/164011106-8b3a48fe-10a2-4b6a-ad0f-1e93b6c5deb5.png">


