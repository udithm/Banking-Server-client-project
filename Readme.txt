In this Implementation of Design and Development of online banking management system,

we have three programs that needs to run simulataneously,

First is server.c, compile-> gcc -o server server.c then run-> ./server
    Initially it will wait for client program to run.
    Then when we start client program and start giving input it gets connected and displays all the accounts that are accessing accessing

Second is data.c, compile-> gcc -o data data.c then run-> ./data

    In this program we will be able create all the data i.e all accounts that can be of any type. 
    First we need to create all admins then when admins accounts are done, then we will add normal users then joint users. 
    If all joint users are done then the program exits.

Third is client.c, compile-> gcc -o client client.c then run-> ./client
    In this first we need to choose which type of account.
    Then we need to give credentials.
    If successfull, then the we can have Deposit, Withdraw, Balance Enquiry, Password Change, View details, Exit options where we select which is required.