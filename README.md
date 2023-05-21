commands for ubuntu


Step 1: Create AddServer.java, AddClient.java, AddServerImpl.java, AddServerInft.java files in a folder
Step 2: Open Terminal and give following commands
javac *.java
rmic AddServerImpl
rmiregistry
Step 3: Create new folder named Server and copy AddServer.class, AddServerImpl.class, AddServerInft.class, AddServerImpl_stub.class
Step 4: Create new folder named Client and copy AddClient.class, AddServerInft.class, AddServerImpl_stub.class


Step 5: open terminal from server folder and give command
java AddServer
Step 6: open terminal from Client folder and give command
java AddClient 127.0.0.1 8 9 (8 and 9 are arguments for addition)


if open in terminal is not there then open directly termonal form menu adn add command cd path to folder 
