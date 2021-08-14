## MEAN STACK DEPLOYMENT TO UBUNTU IN AWS

We are aware of the other application stacks (LAMP,LEMP, MERN) why MEAN ? Why is it so widely adopted, ?  The main reason for preferring MEAN stack over others is because of the use of a single language throughout the development i.e, for both client-side and server-side, since all these technologies are written in JavaScript, web development process becomes neat.

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











