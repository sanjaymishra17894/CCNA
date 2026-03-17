# 09_Network_Troubleshooting_Tools

In this document, we will cover some essential network troubleshooting tools that are frequently used in real-world scenarios. This will include a brief overview of each tool along with examples of packet analysis. We will present the information in both English and Hinglish for better understanding.

## 1. Wireshark

**Overview:**  Wireshark is a powerful network packet analyzer that allows you to capture and view the data traveling across a network in real-time.

**Usage Scenario:**  Diagnosing network problems by inspecting packets for errors, delays, and other anomalies.

**Example:**  Using Wireshark to filter TCP packets by applying the filter `tcp` in the display filter to see the details of the TCP handshake.

**Hinglish:**  Wireshark ek network packet analyzer hai jo aapko real-time mein data ko capture aur view karne ki suvidha deta hai.


---

## 2. Nmap

**Overview:**  Nmap (Network Mapper) is a free security scanner used to discover hosts and services on a computer network.

**Usage Scenario:**  Identifying open ports on a network device to assess security.

**Example:**  Running `nmap -sV 192.168.1.1` to identify the services running on the target machine.

**Hinglish:**  Nmap ek security scanner hai jo aapke network par hosts aur services ko discover karne ke liye use hota hai.


---

## 3. Ping

**Overview:**  A simple tool used to test the reachability of a host on an Internet Protocol (IP) network.

**Usage Scenario:**  Verifying the operational status of a network device.

**Example:**  Using the command `ping 8.8.8.8` to check for network connectivity to Google's public DNS.

**Hinglish:**  Ping ek simple tool hai jo network par kisi host ki reachability ko test karne ke liye istemal hota hai.


---

## 4. Traceroute

**Overview:**  A network diagnostic tool that displays the route and measures transit delays of packets across the network.

**Usage Scenario:**  Identifying routing issues between your computer and the destination server.

**Example:**  Running `traceroute google.com` to see the path taken by packets to reach Google.

**Hinglish:**  Traceroute ek diagnostic tool hai jo network par packets ke route aur transit delays dikhata hai.


---

## 5. netstat

**Overview:**  A command-line tool that provides information about network connections, routing tables, interface statistics, masquerade connections, and multicast memberships.

**Usage Scenario:**  Monitoring active connections and identifying potential security threats.

**Example:**  Executing `netstat -an` to view all active connections and listening ports.

**Hinglish:**  netstat ek command-line tool hai jo aapko network connections aur routing tables ki jaankari deta hai.


---

## Conclusion

Understanding and utilizing these network troubleshooting tools can significantly enhance your ability to troubleshoot issues effectively and efficiently. By mastering these tools, you will be able to analyze network traffic, assess security vulnerabilities, and ensure optimal network performance.