# Networking Basics #0

This project was the initial part of a two-part series introducing networking concepts. It involved answering quiz-like questions and creating bash scripts while exploring topics such as the OSI model, LAN and WAN networks, and TCP/UDP data transfer protocols.

## Tasks :page_with_curl:

### 0. OSI Model
- [0-OSI_model](./0-OSI_model): Text file answering the following questions:
  - What is the OSI model?
    2. The OSI model is a conceptual model that characterizes the communication functions of a telecommunication system without regard to their underlying internal structure and technology.
  - How is the OSI model organized?
    2. From the lowest to the highest level

### 1. Types of Network
- [1-types_of_network](./1-types_of_network): Text file answering the following questions:
  - What type of network is a computer in local connected to?
    3. LAN
  - What type of network could connect an office in one building to another office in a building a few streets away?
    2. WAN
  - What network do you use when you browse www.google.com from your smartphone (not connected to the Wifi)?
    1. Internet

### 2. MAC and IP Address
- [2-MAC_and_IP_address](./2-MAC_and_IP_address): Text file answering the following questions:
  - What is a MAC address?
    2. The unique identifier of a network interface
  - What is an IP address?
    1. Is to devices connected to a network what postal address is to houses

### 3. UDP and TCP
- [3-UDP_and_TCP](./3-UDP_and_TCP): Text file answering the following questions:
  - Which statement is correct for the TCP box:
    1. It is a protocol that is transferring data in a slow way but surely
  - Which statement is correct for the UDP box:
    2. It is a protocol that is transferring data in a fast way and might lose data along the process
  - Which statement is correct for the TCP worker:
    1. Have you received boxes x, y, z?

### 4. TCP and UDP Ports
- [4-TCP_and_UDP_ports](./4-TCP_and_UDP_ports): Bash script that performs the following:
  - Displays listening ports.
  - Shows only listening sockets.
  - Shows the PID and name of the program to which each socket belongs.

### 5. Is the Host on the Network
- [5-is_the_host_on_the_network](./5-is_the_host_on_the_network): Bash script that pings an IP address received as an argument 5 times.
  - Usage: `5-is_the_host_on_the_network {IP_ADDRESS}`.
