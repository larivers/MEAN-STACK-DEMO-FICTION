## MEAN STACK DEPLOYMENT TO UBUNTU IN AWS

We are aware of the other application stacks (LAMP,LEMP, MERN) why MEAN ? Why is it so widely adopted, ?  
The main reason for preferring MEAN stack over others is because of the use of a single language throughout the development i.e, for both client-side and server-side, since all these technologies are written in JavaScript, web development process becomes neat.

## WHAT IS THE MEAN STACK

MEAN is a free and open-source JavaScript software stack for building dynamic web sites and web applications.
 
 M - MongoDB ( Database)
 
 E - Express ( Back-end Web Framework)
 
 A - Angular (Front-end Framework)
 
 N - Node.js (Back-end runtime environment)
 
 
 To proceed with the MEAN Stack deployment, we update and upgrade our linux based OS (Ubuntu).
 
 Next we proceed to install node.js
 
 ![image](https://user-images.githubusercontent.com/24277138/129433562-a97f0725-1345-4ccd-9650-27fe5550b4ef.png)
 
Our database in the stack is MongoDB, hence we need to add the key that will be used to authenticate packages, i.e packages that have been authenticated using these keys will be trusted. 
So we import the GPK key for the mongoDB apt repository

![image](https://user-images.githubusercontent.com/24277138/129433755-bd224a5c-8b53-4cdd-a195-a35c34d590c7.png)

Now we add MongoDB APT repository url in /etc/apt/sources.list.d/mongodb.list, and install mongodb

![image](https://user-images.githubusercontent.com/24277138/129433849-c6cc9570-4697-4aa5-a7f0-5ca3aa06d3cd.png)

![image](https://user-images.githubusercontent.com/24277138/129433966-9cc4fd1c-e8d9-4b74-8e52-4441f054aaca.png)

And the Node package manager and body-parser package is installed.

![image](https://user-images.githubusercontent.com/24277138/129434166-3b75ac70-95ab-4a9d-b823-e152f5e35195.png)

Next we create a Books direcotry and move into it and initialize the npm project

![image](https://user-images.githubusercontent.com/24277138/129434361-accb992a-c6b3-4fef-86bc-d2013c789992.png)

We the web server code into the server.js file.
![image](https://user-images.githubusercontent.com/24277138/129434411-484834bc-fdc7-4a02-b3f2-8c06683a49e6.png)

At this point mongoDB and Node.js has been installed, we will proceed to the Express installation.

![image](https://user-images.githubusercontent.com/24277138/129434487-9ee780e8-8195-4ac7-9915-91a61422dfab.png)

We create a new directory (apps) and move into it

![image](https://user-images.githubusercontent.com/24277138/129434557-6ad539ec-f08d-4e2c-a4b1-2ec4de22c376.png)

Now AngularJS is left, we will use AngularJS to connect to our web page with express

![image](https://user-images.githubusercontent.com/24277138/129434710-e6753e92-e1da-42bf-839f-0e2cdfe59a21.png)

![image](https://user-images.githubusercontent.com/24277138/129434718-8b63300c-1935-4d0c-bad6-536d45e17481.png)









