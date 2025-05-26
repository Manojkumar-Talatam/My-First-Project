# Scanning Of Open Ports
 The goal of this task is to scan the local network to discover the active devices and open ports using **Nmap** which leads to identify the potential risks and makes us to understand the network services. 
# Tools Used
  Nmap-For scanning the IP ranges and to detect the open ports.
# Steps Performed
 1.Installed **Nmap** from official website keeping in mind that to add the Nmap to th system's path.
 2.Opend Command Prompt(not as Administrator)and found the Local IP address range.
 3.Opened Comand Prompt(as Administrator) and verified that Nmap is added by using command *nmap --version*.
 4.Ran a TCP SYN scan by using command *nmap -sS local IP address range*.
 5.Analyzed the live hosts on the network and open ports on each host based on the Nmap results.
 6.Done a reasearch to identify the potential risks and network services from the ports.
