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

## OUPUT - ARP:
<img width="1920" height="1080" alt="Screenshot 2026-05-22 152352" src="https://github.com/user-attachments/assets/8d3b0b62-8fda-466f-961c-50d432fe522c" />


## OUPUT -RARP:
<img width="1920" height="1080" alt="Screenshot 2026-05-22 152403" src="https://github.com/user-attachments/assets/fd9732f0-4cf4-4356-a753-4867c68fb1b3" />

## RESULT
Thus, the python program for simulating ARP protocols using TCP was successfully 
executed.
