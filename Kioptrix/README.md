#Kioptrix Lab Assessement

##Overview 

This project documents my reconnaissance and enumeration of the kioptrix vulnerable virtual machine in an isolated VirtualBox lab.

## Lab Environment 

-Attacker: Kali Linux

-Target: Kioptrix 

-Target IP: 192.168.56.104

-Network: VirtualBox Host-Only Network.

##Objectives 

-Discover the target marchine.

-Identify open ports and services.

-Perform service and version detection.

-Investigate SMB services.

-Examine SSL/TLS configurations.

-Identify potential security weaknesses.

## Tools Used

-Nmap

-Netdiscover

-smbclient

-curl

-Kali Linux


## Key Findings

-SSHv1 support identfied 

-Apache 1.3.20 identified 

-SMB anonymous access observed.

-SSLv2 support identified.

-HTTP TRACE method identified.

## Current Status

Reconnaissance and enumeration completed. Further vulnerability validation and exploitation are pending.
