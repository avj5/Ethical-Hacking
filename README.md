# Ethical-Hacking

For our project we decided to do our project over wireshark packet analysis.

#### WireShark
We used Wireshark to analyze the packets that we were getting sent to us.
Link to Wireshark: https://www.wireshark.org/download.html

#### Kali Linux
To do this project we had to use a two Virtual Machines. We used Kali Linux to be able to conduct our research and observations. We just had to get two VMs to connect with each other and then we could send packets between them.
Link to Kali: https://www.kali.org/get-kali/#kali-virtual-machines

#### Project steps
##### Step 1
First we created a fake account on a practice website. We entered fake information and then logged in. While doing this we start a wireshark packet capture. After we Logged in, we checked the packets and in finding the right one we could see the exact account information we entered into the website on wireshark.

##### Step 2
Sent SYN packets across one VM to another VM. Doing this we saw all of the SYN packets on wireshark. This also showed us all the ports on the target computer. We also saw a lot of half open ports and handshakes that shut down the connection.

##### Step 3
In this step we created a Three-way Handshake between the computers. Which didn't actually work for us, but we ended up getting one to show up for us on the same computer if we just went to a google browser.

#### Step 
