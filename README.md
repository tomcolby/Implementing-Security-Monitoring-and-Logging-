# Implementing-Security-Monitoring-and-Logging

## Objective
In this lab, I will learn about several tools and techniques that serve different monitoring and logging needs. I will begin by exploring the Windows Event Viewer, which can be used to record and analyze security events on Windows hosts. Next, I will configure an Intrusion Detection System on a pfSense firewall, which is used to actively monitor network traffic for malicious activity. In Section 2, I will learn to navigate log files in a Linux environment, as well as configure a file integrity monitor, which is used to detect changes at the filesystem level.


### Skills Learned
- Navigate the Windows Event Viewer and identify failed log-in entries.
- Deploy an Intrusion Detection System to monitor the network for suspicious traffic.

- Navigate Linux system logs and identify failed log-in entries.
- Configure a Linux system to transfer log data to a remote syslog server.
- Deploy a file integrity monitor to track changes to critical system files.

### Tools and Software Used
- Windows Event Viewer
- pfSense
- Snort
- Tripwire

### Topology
- vWorkstation (Windows: Server 2022)
- Switch01 (Linux: Debian 11)
- pfSense (FreeBSD: pfSense)

### Lab Overview
STEP 1 of this lab has two parts, which should be completed in the order specified.
 
- I will use the Event Viewer to identify failed logon attempts in a Windows environment.
- I will configure the Snort IDS to monitor for intrusions on the network.


STEP 2
- I will identify failed logon attempts in a Linux environment and configure Tripwire to monitor file integrity.


<h2>Program walk-through:</h2>

## STEP 1
### Part 1: Identify Failed Logon Attempts on Windows Systems

<p align="center">

</p>

### Part 2: Monitor Network Activity with Snort
<p align="center">

</p>

## STEP 2
### Part 1: Identify Failed Logon Attempts on Linux Systems

<p align="center">

</p>

### Part 2: Monitor File Integrity with Tripwire
<p align="center">

</p>
