# Wireshark Project

## Project Description: 
Capture TCP traffic and analyze. TCP packets start with a handshake (ensures the Host & Destination are ready to communicate. Both check each others open ports by sending a (SYN) packet. Need to test packets are being sent and recived and are being encrypted.


## Project Procedure: 
1. Start wireshark
2. Choose the network interface that is being used for your internet connection. 
3. Capture Interface. (Wireless)

4. Selected a Packet to analyze (A request that was sent to IP address: 239.255.255.250)

5. Selected the IP information (Internet Protocal)

6. Checked out the TCP layer more in depth since that is the source of my request. Source Port: 56185  Destination Port: 1900.
NOTE: Ports 1-1023 are Standard Ports. I used Port 443 for analysis.


## Project Data Analysis: 
Selected, “Follow TCP Stream” 
Results: All the messages in the packet were encrypted when sent across the network. This confirms that TCP layer is encrypted.


## Project Documentation:

![pc#1](https://user-images.githubusercontent.com/28675258/66273919-d62ae180-e846-11e9-8ef6-2c33a9ca151e.PNG)

![pc#2](https://user-images.githubusercontent.com/28675258/66273921-da56ff00-e846-11e9-9abf-8e203760b609.PNG)

![pc#3](https://user-images.githubusercontent.com/28675258/66273923-ddea8600-e846-11e9-842d-7e099b4b9f00.PNG)

![Capture Interfaces (Specif filter)#2](https://user-images.githubusercontent.com/28675258/66273927-e5119400-e846-11e9-8b21-2a3e499dbc88.PNG)

![pc#4](https://user-images.githubusercontent.com/28675258/66273924-e17e0d00-e846-11e9-8e8e-e89359e0421d.PNG)






