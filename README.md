# Wireshark Project#1

## Project Description: 
Capture TCP traffic and analyze. TCP packets start with a handshake (ensures the Host & Destination are ready to communicate. Both check each others open ports by sending a (SYN) packet. Need to test packets are being sent and recived and are being encrypted.

## Project Procedure: 
1. Start wireshark
2. Choose the network interface that is being used for your internet connection. 
3. Capture Interface. (Wireless) [pc#1)

4. Selected a Packet to analyze (A request that was sent to IP address: 239.255.255.250)

5. Selected the IP information (Internet Protocal) [pc#2]

6. Checked out the TCP layer more in depth [pc#3] since that is the source of my request. Source Port: 56185  Destination Port: 1900.
NOTE: Ports 1-1023 are Standard Ports (Port 80 is used for HTTP)

## Project Data Analysis: 
1. Selected, “Follow TCP Stream” 
Results: All the messages in the packet were encrypted when sent across the network. ” [pc#4]. This confirms that TCP layer is encrypted. 
