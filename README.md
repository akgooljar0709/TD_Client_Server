## TD CLIENT SERVER BY GOOLJAR AKASH
The purpose of this project is to create a client-server application and to set up a communication protocol.
communication between the two entities.


## Install the python3 libraries
To install these libraries, type the following commands in a terminal:
```sh
sudo apt install python3-numpy
sudo apt install python3-pip
sudo pip3 install pillow
```
## Install
Make a git clone of the git repository on server and client

```sh
git clone https://github.com/akgooljar0709/TD_Client_Server.git
```
We should run the server.py first on the server side
To run the script on server side:

### SERVER / CLIENT STEPS AND EXPLANATION

1. We need to change the ip address of the server onto the server.py : To change the ip address
   we need to change the ip on the function accept_connections.
2. Run the server.py on the server
3. Enter the port you want to use(eg: 4500)
4. Then run client.py on the client
5. Enter the same ip address and port used on the server side
6. Both the server and the client will be able to communicate
7. The client will need to type the filename of the image he wants to download(eg: img.jpg)



### SERVER SIDE
```sh
python3 server.py 

10.27.0.42
Enter desired port --> 4500
Running on IP: 10.27.0.42
Running on port: 4500
```




### CLIENT SIDE
```sh
python3 client.py 

Enter ip --> 10.27.0.42
Enter port --> 4500
Enter file name on server --> img.jpeg
img.jpeg successfully downloaded.
0b1010011011
pair
impair
```


## Communication protocole used
- TCP

TCP stands for Transmission Control Protocol a communications standard that enables application programs and computing devices to exchange messages over a network. 

It is designed to send packets across the internet and ensure the successful delivery of data and messages over networks.

## client . py Script

The client.py should be placed on the client side
It should have the same ip address as the server side.


The scripts help to make communications between server and client.

## server. py Script Installation

The server.py should be placed on the server side.

The scripts help to make communications between server and client.


