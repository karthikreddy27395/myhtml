deploying a html website    
create a amazon ubuntu machine and also give http port 80 in security groups while cretaing it   
download mobaxterm in your laptop   
copy ubuntu instance public ip address   
access the instance in mobaxterm by giving following details   
remote host = ip address   
specific name = ubuntu   
and .pem file in additional settings   


code  

sudo su   
apt-get update   
apt install docker.io   
service docker start   
docker pull ubuntu   
docker run -itd --name container1 -p 80:80 ubuntu   
docker exec -it container2 bash   
apt-get update -y   
apt install apache2 -y   
cd /var/www/html/   
ls   
apt install vim -y   
vim index.html       //you will goto the index page    




i                 //then change the title at head as karthik website   
:wq   
echo "hi this is karthik's website" >index.html   




     //then open the ip address followed by:80 port 
     //the html page will be displayed



