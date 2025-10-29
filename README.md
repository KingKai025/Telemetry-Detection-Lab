# Telemetry-Detection-Lab
Simulating adversary attack with Splunk powered detection amongst other things...

---

## Objective
Gaining unauthorized entry into a windows machine and establishing a remote connection and verifying the attacks detection using Splunk.

## Tools
- msfvemon and msfconsole
- setoolkit
- Splunk


## Adversary Attack
### Generate a payload using msfvenom to be used to establish the remote connection
- scan the network for available devices
<img width="1548" height="853" alt="Screenshot (435)" src="https://github.com/user-attachments/assets/ac7a0a67-3182-43cf-bb53-3ecac21a5680" /> <br/>
*Ref 1: Scanning available devices* <br/>
<br/>

- scan target device to probe more information out of it
<img width="1591" height="829" alt="Screenshot (437)" src="https://github.com/user-attachments/assets/a0d7fad9-f520-4815-894b-3857bc7dbe7a" /> <br/>
*Ref 2: Port scanning*
<br/>

- generate the payload to be sent to the device
<img width="1421" height="390" alt="Screenshot (439)" src="https://github.com/user-attachments/assets/f86c4432-7864-4f67-96fa-d4704cc0eeef" /> <br/>
*Ref 3: Generating payload* <br/>
<br/>
<br/>

### Opening the handler to listen in on the malware
- configure msfconsole to listen in on the malware to establish a remote connection to the target device
<img width="1423" height="732" alt="Screenshot (441)" src="https://github.com/user-attachments/assets/e9307043-613b-47c3-b1a6-6834f3672d14" /> <br/>
*Ref 4: Establishing remote connection*
<br/>
<br/>

### Exfiltrating confidential data 
- finding any confidential documents and exposing it's juicy secrets
<img width="1427" height="338" alt="Screenshot (451)" src="https://github.com/user-attachments/assets/dc8e1c1e-00b7-4408-9393-8a95da51387f" />
<img width="1427" height="476" alt="Screenshot (452)" src="https://github.com/user-attachments/assets/117e315f-05b5-4e2f-a4b6-531ee3e5a7e7" /> <br/>

*Ref 5: Revealing sensitive information*
<br/>
<br/>

## Telemetry Generation
- investigating suspicious activity in the system after a notepad opened on it's own. <br/>

https://github.com/user-attachments/assets/e0535c8b-2772-4983-984b-f7b73854b2c4 


*Ref 6: Suspicious activity & malware investigation*



