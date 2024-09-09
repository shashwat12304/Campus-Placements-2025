Round-1 

Question 1 (Medium Level)

An IP (Internet Protocol) packet is a message that is sent to the destination network with lots of information. Each packet has its own header and payload. The IP header has enough information to send the packet to the designated receiver, so the the receiver can identify if the packet is correct information before forwarding to the application layer. Let us consider the below IP header. You are expected to finish the below program to parse the IP header information given as input, and print the parsed information as given in the below example.

For example, consider the below input to the program.

01000000011000110000000000011000
11000000101010000000000101110101 
11000000101010000000101101001111

Function Description

Complete the function parselPHeader in the editor below.
parselPHeader has the following parameter(s): 
str packetData[n]: 3 lines of input data depicting the IP packet header.

Sample Input 
     3
     01000000011000110000000000011000
     11000000101010000000000101110101
     11000000101010000000101101001111

Sample Output 
     4, TCP,48,48
     192.168.1.117
     192.168.11.79

     
Question 2 (Medium level)

In order to uniquely identify the devices on the computer network, each device is allotted an Internet Protocol address (IP address). There are 2 versions of address formats in use i.e. IPv4 which 32 bits in length and IPv6 having 128 bits. Modern devices use IPv6 but in order to communicate with devices supporting only IPv4, the conversion from IPv4 to IPv6 and vice versa. Also, the IPv4 addresses of the format 127.x.x.x (where x means any octet value) are the loopback addresses and the equivalent of it in IPv6 is:: 1. Consider the IP address 192.168.10.92. The 4 octets of the IP address would be 192, 168, 10 and 92 and the hexadecimal equivalent of these octets are CO, A8, 0A and 5C. Then, the first and second are concatenated and third and fourth are concatenated to get COA8 and 0A5C. Finally, the IPv6 is formed as ::FFFF:C0A8:0A5C. (The FFFF in the IPv6 address is a constant and should appear in all IPv4 to IPv6 converted address except the loopback address. Similarly, any input IPv4 address which is a loopback address, the output should be :: 1. You are expected to finish the function with takes a the IPv4 address as a parameter and print the IPv6 equivalent of it.

Question 3 (Easy level)

Coding Question based on string and sequence 

Question 4 – 23 MCQs

•	Java Language Code 
•	Bash Shell commands
•	Operating system 
•	Networking ( TCP , UDP, IPv4, IPv6…etc)
•	Linux & its commands
•	Time complexities



