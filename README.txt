This simple project for Docker deployment on AWS ec2.

how to make this webstatic hosting page .

1) Creating docker image on vscode 
2) push image on dockerhub
3) Create aws ec2 instance 
4)install docker on aws ec2 instance
5)pull the image on your ec2 instance
6)Run conatiner with port binding
7)Access your website from browser

make sure first run this command 
npm install (to create the file node_module)
then 
ec2 instance run command
yum inatll docker -y

systemctl start docker & systemctl enable docker //your docker now start to run/build

docker pull <dockerhubname-image> 

docker images (//create image)

docker build . -t <imagename:tag>  //to build the your image.

docker run --rm -d -p 80:3000 <imagename:tag> (//to create and run the container)
after

copy ipadd:80  hit from browser