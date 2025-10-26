# Telemetry-Detection-Lab
Simulating adversary attack with Splunk powered detection amongst other things...

---

## Objective
Gaining unauthorized entry into a windows machine and establishing a remote connection and verifying the attacks detection using Splunk.

## Tools
- msfvemon and msfconsole
- setoolkit
- Splunk
- wireshark
- zphisher
- burpsuite

## steps
### Generate a payload using msfvenom to be used to establish the remote connection
- scan the network for available devices
- scan target device to probe more information out of it
- generate the payload to be sent to the device

### Opening the handler to listen in on the malware
- configure msfconsole to listen in on the malware to establish a remote connection to the target device

### creating a spear-phishing email
- after setting up the listening device, it's time to send the phishing the email and want for the target to click the bait.

  
- creating a back door to be used over and over again
- exfiltrating confidential data 
