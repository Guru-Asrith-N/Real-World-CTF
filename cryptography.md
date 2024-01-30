# cryptography

opened the attachments  
opened the packet.pcap in wireshark since it is a packet capture type of file  
went through each code manually and realized that all ssh packets are named as encrypted packets  
applied filters in wireshark for ssh packets and found 4 such packets   
opened each packet and found encrypted codes in them  
thought that they were hexadecimal encryption since only numbers ad letters form a to f are used   
checked it in 'Boxentriq' and found that they were hexadecimal encrypted   
tried to convert them to text using converter  
didn't work  
so went through the github writeup given along with attachment   
opened password.go in the github repo   
noticed base64 in it so tried to use it but it didn't work  
went through other files in the github repo but didn't find anything else  
