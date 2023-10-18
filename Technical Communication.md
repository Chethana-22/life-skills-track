# What is Firewalls and How does it work ?

## Table of Contents

- [Introduction](#introduction)
- [Why Firewalls?](#why-firewalls)
- [Types of Firewalls](#types-of-firewalls)
- [Advantages of Firewalls](#advantages-of-firewalls)
- [Limitations of Firewalls](#limitations-of-firewalls)
- [References](#References)


## Introduction

With the increasing in accumulation of big data and cyber crimes, there is the necessity of securing one's information. A firewall hepls to safeguard your networka and device from the intruders. Firewall is a network security device that filters and observes the incoming and outgoing network traffic, by adhering to the seci=urity policies of a particular organization. It acts as a protective wall between the internal network and the public internet.
Firewalls are used in enterpise and also in personal settings. They play cruial role in network security. Many Operating systems bear a build-in firewalls.

## Why Firewalls ?

The primary purpose of firewalls is to scrutinize incoming and outgoing network traffic, permitting or denying it based on predetermined security rules and policies. By effectively filtering traffic, firewalls help prevent malicious entities from infiltrating a network, protecting sensitive data, applications, and infrastructure from a range of threats, including viruses, malware, hackers, and other cyberattacks. Additionally, firewalls can be used to enforce network policies, control access to specific resources, and ensure compliance with regulatory requirements, making them a fundamental tool in maintaining the confidentiality, integrity, and availability of digital assets in an increasingly interconnected world.

## Types of Firewalls

Firewalls can either be software or hardware. Software firewalls are programs that are install on each computer, meanwhile the hardware firewalls are the equipments that are established between the gateway and your network. There are many types of firewalls, few are 

#### 1. Packet Filtering
A packet filtering firewall controls data flow to and from a network. It allows or blocks the data transfer based on the packet's source address, the destination address of the packet, the application protocols to transfer the data, and so on

#### 2. Stateful Firewall
Stateful firewalls, also known as dynamic packet filtering firewalls, are an advancement over packet filtering firewalls. They keep track of the state of active connections and make decisions based on the context of the traffic. For example, they can allow incoming response packets for an outgoing connection initiated from within the network. This stateful inspection makes them more secure than stateless packet filters.

#### 3. Proxy Firewalls
They act as intermediaries between the internal network and external services. When a user requests access to a resource, the firewall fetches it on behalf of the user, inspecting and filtering the content in the process. This adds an additional layer of security and privacy but can introduce latency.


## Advantages of Firewalls
- **Network Security**: Firewalls hepl to prevent the unauthoriazed access and protect against external threats
- **Resource Management**: They can be used for managing network resources, like bandwidth or CPU usage
- **Application Control**: Firewalls allow you to control what applications are allowed on a computer system
- **Data Encryption**: Some firewalls have built in encryption capabilities that encrypt data before it leaves your network
- **Protection Against Malware**: By blocking malicious traffic, firewalls help in securing your system from malware attacks
- **Intrusion Detection/Prevention**: They help identify any malicious activity that may occur within an organization's network

## Limitations of Firewalls
- **Complexity**: Setting up and maintaining firewalls requires technical knowledge
- **Performance Overhead**: Some firewall solutions may have performance overheads that affect overall network performance.
- **Limited by Resources**: The number of rules that can be created within a firewall will depend on the amount of available memory and processing power.

## References

1. Digital Ocean - [https://www.digitalocean.com/community/tutorials/what-is-a-firewall-and-how-does-it-work]
2. Simplilearn Blog - [https://www.simplilearn.com/tutorials/cyber-security-tutorial/what-is-firewall]
3. Geekforgeeks - [https://www.geeksforgeeks.org/introduction-of-firewall-in-computer-network/]