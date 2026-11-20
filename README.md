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
<img width="849" height="762" alt="image" src="https://github.com/user-attachments/assets/a3170d00-03cf-4e6b-8ddf-9184ea6b796c" />

## OUPUT - ARP
<img width="1082" height="276" alt="image" src="https://github.com/user-attachments/assets/91eb620e-6660-448c-b69d-638a014fa59f" />

## PROGRAM - RARP
<img width="483" height="386" alt="image" src="https://github.com/user-attachments/assets/ac0fcb52-22c8-407b-9929-12dd13351f02" />

## OUPUT -RARP
<img width="1050" height="206" alt="image" src="https://github.com/user-attachments/assets/382863cf-7525-4dc6-bb92-ac980579f9ca" />

## RESULT
Thus, the python program for simulating ARP protocols using TCP was successfully 
executed.
