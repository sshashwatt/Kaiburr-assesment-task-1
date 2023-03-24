# Task 1: Java REST API Example

## Rest Api Endpoints
* Put a server ```http://127.0.0.1:2017/addServer``` Add "server" object in JSON form.

* GET servers ```http://127.0.0.1:2017/getServers``` Returns a list of "server" objects.

* GET server by id ```http://127.0.0.1:2017/getServers/{id}``` Returns a "server" object matching with id.

* GET servers by name ```http://127.0.0.1:2017/getServer/{name}``` Returns a list of "server" objects matching with name.

* DELETE server by id ```http://127.0.0.1:2017/deleteServer/{id}``` Deletes a "server" object matching with id. 

## Testing APIs on POSTMAN

ScreenShots

* ##### Adding Server 
![AddingServer](https://github.com/sshashwatt/Kaiburr-task-1/blob/main/Task1/ScreenShots/AddingServer.png)

* ##### Get Servers : Here we get all the servers present in database.

![GetServers](https://github.com/sshashwatt/Kaiburr-task-1/blob/main/Task1/ScreenShots/GetServers.png)

* ##### Get Server By Id : Here we get only one server for the given id and if there is no server for given id then we get status as ``` 404 NOT FOUND ```.
Get Server By Id
![GetServerById](https://github.com/sshashwatt/Kaiburr-task-1/blob/main/Task1/ScreenShots/GetServerById.png)

```404 NOT FOUND```
![GetServersById(404 not found)](https://github.com/sshashwatt/Kaiburr-task-1/blob/main/Task1/ScreenShots/GetServersById(404%20not%20found).jpg)

* ##### Get Server By Name : Here we get all servers by name and if there is no server then we get ```404 NOT FOUND```. 

![GetServerByName](https://github.com/sshashwatt/Kaiburr-task-1/blob/main/Task1/ScreenShots/GetServerByName.png)

```404 NOT FOUND```
![GetServersByName(404 not found)](https://github.com/sshashwatt/Kaiburr-task-1/blob/main/Task1/ScreenShots/GetServersByName(404%20not%20found).png)


* ##### Delete Server : Here the server gets deleted for a given id.
![DeleteServer](https://github.com/sshashwatt/Kaiburr-task-1/blob/main/Task1/ScreenShots/DeleteServer.png)

* #### MongoDB database 
![MongoDBDatabase](https://github.com/sshashwatt/Kaiburr-task-1/blob/main/Task1/ScreenShots/MongoDBDatabase.png)


## Thank You !!!


