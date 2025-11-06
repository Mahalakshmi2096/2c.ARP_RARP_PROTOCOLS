# 2c.SIMULATING ARP /RARP PROTOCOLS
## AIM
To write a python program for simulating ARP protocols using TCP.
## ALGORITHM:
## Client:
1. Start the program
2. Using socket connection is established between client and server.
3. Get the IP address to be converted into MAC address.
4. Send this IP address to server.
5. Server returns the MAC address to client.
## Server:
1. Start the program
2. Accept the socket which is created by the client.
3. Server maintains the table in which IP and corresponding MAC addresses are
stored.
4. Read the IP address which is send by the client.
5. Map the IP address with its MAC address and return the MAC address to client.
P
## PROGRAM - ARP

Client:  

<img width="961" height="562" alt="image" src="https://github.com/user-attachments/assets/505ea7ac-94a7-448a-8335-c83c3cce081f" />

Server:

<img width="958" height="567" alt="image" src="https://github.com/user-attachments/assets/c33be658-b7e3-4c0f-9747-5a71f4c3fee5" />

## OUPUT - ARP

Client:

<img width="956" height="567" alt="image" src="https://github.com/user-attachments/assets/8dd0870e-f40d-4800-be89-33d2797c154b" />

Server:

<img width="956" height="562" alt="image" src="https://github.com/user-attachments/assets/e43e0b46-c544-4423-a44f-1ae0792cb8a5" />

## PROGRAM - RARP

Client:  

<img width="957" height="567" alt="image" src="https://github.com/user-attachments/assets/27628f4e-e7b6-48b9-a0ff-ae93731b9155" />

Server:

<img width="957" height="566" alt="image" src="https://github.com/user-attachments/assets/8959bee6-e4b9-4f45-b8f8-d6ac42c0ec2c" />

## OUPUT -RARP

Client:

<img width="958" height="565" alt="image" src="https://github.com/user-attachments/assets/b4a6b4f8-f54e-4f92-bed0-6fdd51fe4167" />

Server:

<img width="957" height="568" alt="image" src="https://github.com/user-attachments/assets/1c5b5701-7928-4a11-9ac9-e2d6da2db38a" />

## RESULT
Thus, the python program for simulating ARP protocols using TCP was successfully 
executed.
