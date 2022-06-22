
This repository contains code for my solution prototype built as part of Microsoft's Cybersecurity Engage program 2022.


I have used fernet cryptography which is an authenticated cryptography which doesn't allow to read and modify file without having key.
# TO ENCRYPT A FILE
We initialise a fernet object and pass our key to it and store it as a local variable and we read our original data
and then we encrypt the data using out fernet key and it encrypts the file
# TO DECRYPT A FILE
 To Decrypt the file the process is reverse of encryption, We create a fernet object and pass our encryptd key to it,
 and we decrypt the data using the ferent object 
 This prototype implements an element of cryptography in the communication between the PNC and field devices 
