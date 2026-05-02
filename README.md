http://github.com/sudip7407/Repo2

#! /bin/bash

apt-get update

apt-get install -y nginx

systemctl start nginx

systemctl enable nginx

apt-get install -y git

curl -SL https://deb.nodesource.com/setup_16.x|sudo -E bash -

apt-get install -y nodejs

git clone

cd

npm install

node index.js

assg 9: (sudo apt-get update)

(sudo apt-get upgrade)

(sudo apt install nginx)

(curl -SL https://deb.nodesource.com/setup_16.x|sudo -E bash -)

(sudo apt install nodejs)

(git clone “Paste the project repository link”)

(dir)

(cd “repository name”)

(npm install)

(node index.js)

assg 7:

pwd ls ‘sudo apt-get update’ ,

‘sudo apt-get upgrade’ , ‘sudo apt-get install nginx’ nginx -v cd .. cd .. cd var cd www sudo chmod 777 html

Asg 11: 19. Now enter the command: nano infy.sh After the command a new nano Editor window will open. Type the following in it. #! /bin/bash while true do echo "loop running" done And save it by ctrl+X And type this command: chmod +x infy.sh And run the file by ./infy.sh

Asg 8: Initialize Git

git init

 Add all files to the current working tree

git add .

 Status of the Working Tree

git status

 Set Global user Email

git config --global user.email

 Set Global User Name

git config --global user.name

 Commit changes to the working tree with a message

git commit -m “Done”

 Add the repository address

git remote add origin

 Push The committed changes

git push -u origin master

Asg 12: pwd cd / ls cd etc/nginx/sites-available ls sudo nano default

In location: location / {

proxy_pass http://localhost:4000;

proxy_http_version 1.1;

proxy_set_header Upgrade $http_upgrade;

proxy_set_header Connection 'Upgrade';

proxy_set_header Host $host;

proxy_cache_bypass $http_upgrade;

}

sudo systemctl restart nginx

<!DOCTYPE html>
<html>
<head>
    <title>My Static Website</title>
</head>
<body>
    <h1>Welcome to My Website</h1>
    <p>This is the home page hosted on AWS S3.</p>

    <a href="about.html">About</a> |
    <a href="contact.html">Contact</a>
</body>
</html>

<!DOCTYPE html>
<html>
<head>
    <title>About Me</title>
</head>
<body>
    <h1>About Me</h1>
    <p>Hello! I am learning to build static websites using AWS S3.</p>

    <a href="index.html">Home</a> |
    <a href="contact.html">Contact</a>
</body>
</html>

<!DOCTYPE html>
<html>
<head>
    <title>Contact</title>
</head>
<body>
    <h1>Contact Me</h1>
    <p>Email: example@email.com</p>

    <a href="index.html">Home</a> |
    <a href="about.html">About</a>
</body>
</html>
