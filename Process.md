### Worrking on ec2 
1. Install jenkins from official website 
2. Install docker on same ec2 instance
3. add your current login user and jenkins user to the docker group and login to that group to aviod the docker not found conflict

### Install sonarqube on docker container 
1. docker run -itd --name sonarqube_server -p 9000:9000 sonarqube:lts-community
2. open port localhost:9000 or ec2 instance public_ip:9000 username:admin, password:admin
3. set your own password 

### Install trivy on macos
1. brew install trivy
    
