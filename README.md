deploying a html website        
create a amazon linux machine and also give http port 80 in security groups while cretaing it
download mobaxterm in your laptop
copy amazon linux instance public ip address


code

sudo su
sudo yum update -y
sudo amazon-linux-extras install docker -y
sudo service docker start
docker pull ubuntu
docker run -itd --name container2 -p 80:80 ubuntu
docker exec -it container2 bash

