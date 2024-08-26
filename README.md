# Azure-SIEM-Deployment

## Objective
•	Establish a Virtual environment in order to simulate SIEM intelligence gathering events on RDP port. 💻

### Skills Learned
•	Deploy and Configure Virtual Machine in Azure 
•	Connect and Ingest Event Logs from VM to Microsoft Sentinel for review 
•	Collect RDP Port Traffic in Test Environment to monitor unauthorized login attempts 
•	Rule Creation for security events categorized by severity to trigger incident alerts 

### Tools Used ⚙
•	Microsoft Azure VM
•	Microsoft Sentinel 

## Steps

Examples below.

Creating VM with RDP allowing inbound traffic 
![VM Port Rules](https://github.com/user-attachments/assets/db2980fe-967e-4904-bbcb-2e1e36387896)

VM Deployed/Running 
![VM Deployed](https://github.com/user-attachments/assets/bd9bf3d8-7ba2-4ebe-8e95-0daad92b6cef)

Create Sentinel Log Workspace 
![Create Sentinel Log Workspace](https://github.com/user-attachments/assets/b4cd3439-40df-4c97-bcff-126caf5b6f79)

VM Port Rules are defined 
![Inbound Port Rules](https://github.com/user-attachments/assets/a7f607c2-9de1-408e-b1ed-6a59a4d69fd4)

Connecting VM Events to Sentinel 
![Connecting Windows VM to Sentinel](https://github.com/user-attachments/assets/76d9f9e7-ca65-4404-ba69-822af7f6ef6d)

Security Events successfully connected 
![Events connected to Sentinel](https://github.com/user-attachments/assets/c7d9ef2d-0e95-443d-8fbd-8f908aac30c6)

Logs Successfully Recieved 

![Logs Sucessfully Recieved](https://github.com/user-attachments/assets/2e74b4d0-f5b4-496b-b236-529efcbbd02c)

Logs Displayed in Sentinel 
![Logs Collected in Sentinel](https://github.com/user-attachments/assets/21d5eb83-d8b0-4168-b56d-4e6b97c6ba53)

Creating Rule for Unauthorized Successful Log Ins to trigger alert 
![Creating High Alert Rule in Sentinel](https://github.com/user-attachments/assets/272dfb41-ba33-4570-9915-c8160496d9ad)


Query Settings for Alert 
![Setting Query Settings](https://github.com/user-attachments/assets/f750486c-48bc-49de-979e-8767144d7b4d)

Log Events 
![Log Events 2](https://github.com/user-attachments/assets/be8fb34a-19e6-4ba0-8690-dea0b893e829)

Alert Rule Successfully Created 
![Alert Rule Created](https://github.com/user-attachments/assets/35d49927-5dac-4ac0-a96c-661bbd32b987)

Connecting to RDP
![Connecting to RDP](https://github.com/user-attachments/assets/3e545662-493f-44f5-a3d9-9ec26b346a37)

Security Event Trigger Logged on Incident Dashboard 
![Sucessful Sign in Incident Recorded](https://github.com/user-attachments/assets/beb9491b-0aaa-4187-b1d1-98e4189f6069)
