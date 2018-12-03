#### Transparent Data Encryption (TDE) Implementation

1. In order to start this process you need to create the master key in the master database.
![create master](https://github.com/tjs6f2/IT2910Final/blob/master/TDE%20Screenshots/create%20master%20key.PNG)

***

2. Once you have created the master key, you will need to create the certificate
![create cert](https://github.com/tjs6f2/IT2910Final/blob/master/TDE%20Screenshots/create%20cert.PNG)

***

3. Next we need to create a connection between the certificate and the database we want to encrypt 
![create connection](https://github.com/tjs6f2/IT2910Final/blob/master/TDE%20Screenshots/create%20db%20key.PNG)

***

4. Then we want to enable the connection to encrpyt the database
![enable](https://github.com/tjs6f2/IT2910Final/blob/master/TDE%20Screenshots/enables%20connection.PNG)

***

5. Test to see if encprytion is working. Encryption_State will be set to 3 if implemented correctly
![test](https://github.com/tjs6f2/IT2910Final/blob/master/TDE%20Screenshots/key%20and%20cert%20confirmed%20created.PNG)

***

6. Backup the certficate
![backup](https://github.com/tjs6f2/IT2910Final/blob/master/TDE%20Screenshots/backup%20cert.PNG)
