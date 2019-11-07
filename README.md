# 👨‍🍳 Restaurant Management System

## Project Description
DineOut is an **Android based Restaurant Management System** that aims to digitalize the process of various restaurant operations including **ordering, billing kitchen, hall and inventory management**. 

The main purpose is to **improve the performance** of the restaurant by eradicating the daily paperwork. With this system the tasks
would be performed in less amount of time and more efficiently. An additional benefit of this software is that during the rush hours the load can be balanced effectively, and restaurants would perform better than usual. In addition to this, human error that occurs when performing tasks manually is also minimized and presence of queues in the system to assign tasks to chefs can reduce congestion in the kitchen. The system would also result in reduction of labor which would result in the reduction of expenses of the restaurant. Feedback module would help the restaurant check for how well they are performing, and monthly/yearly figures can be checked by the billing module to see the trends in sales and profits. These benefits can potentially result in generation of more revenues for the restaurant. 


## User Classes and Characteristics
There are **five** types of users for our system. 

### 1. Customer Class
Customers interact with our system directly in order to place order, modify order, get bill and give feedback. We do not store any information related to customers in our system. The process of order taking starts from customers placing order and then the other series of events begin.

### 2. Head Chef/Kitchen Manager
Head Chef can mark a dish as prepared when a chef tells him to do so. He can approve the cancellation of an order whenever a customer edits or removes a dish from his order. He can also assign a dish to a particular chef based on the specialty of the chef.

### 3. Chef
Chefs don’t interact with the system. They just have to look at the dishes present in their queues and prepare the dishes accordingly. Chef’s name, address and specialty etc. are stored in the database.

### 4. Admin
Admin’s job is to manage the inventory and other information related to menu and chefs in the system.

### 5. Hall Manager
Hall Managers will provide its input when he marks the bill as paid when customers pay for their order or get the bill printed. Moreover, he gets a notification whenever a particular order is complete, or some customer asks for help through the system. Hall manager can also see tables in the hall and their status i.e. empty or filled.


## How to Run

In order to have a look at the code files and understand the working, simply download this repository and open Android Studio and browse to the downloaded project and open it. It will load the project files and the code will be ready to run. 

Before running the app, use your Google Account to register this Application on Firebase Console, with any name you want. I have provided a copy of the **Firebase Database** [Firebase Realtime DB Backup](../master/database/Firebase%20Realtime%20DB%20Backup.json). Download it and import it in the Firebase console. Then you will have a working Database for the app. After that using your Google Account, login to Android Studio. Then you can run the project.

The login credentials for Admin, Hall and Kitchen Manager's interfaces are:
- admin@gmail.com
- chef@gmail.com
- hallmanager@gmail.com

All have the password: 123456


---
## 👨🏼‍💻 Contributors
It was really fun to work with these geeks to get the job done:
#Andrew Kinyanjui
#Stack Overflow 
---

## My Contact
+254714425116

If you liked the repo then please support it by giving it a star ⭐!


## License
Hakuna brathee

Copyright (c) 2019-present, Andrew Kinyanjui                                                        
