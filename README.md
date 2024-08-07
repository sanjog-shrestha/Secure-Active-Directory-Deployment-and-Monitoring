# Secure Active Directory Deployment and Monitoring

## Objective

The objective of this project is to set up a secure Active Directory environment, integrate a SIEM (Splunk) system for comprehensive monitoring and analysis, and conduct penetration testing and red teaming activities to evaluate the overall security posture of the domain infrastructure.

### Skills Learned

- Active Directory Administration
- Security Monitoring and Analysis
- Penetration Testing and Red Teaming
- Threat Detection and Response
- Virtualization


### Tools Used

- Active Directory
- Splunk
- Kali Linux
- Atomic Red Team

## Steps

![image](https://github.com/user-attachments/assets/5aa1b218-f1a8-467a-9a4c-fe99637a2622)

Ref 1: Network Diagram

![image](https://github.com/user-attachments/assets/17b10571-4983-4ab7-9243-abf0067312ac)

Ref 2: Installation of splunk server

![image](https://github.com/user-attachments/assets/8c76c6e5-d86f-40c6-a31b-3b1d3ae77a95)

Ref 3: Creation of Windows Server Local Server

![image](https://github.com/user-attachments/assets/76b7d692-ab40-4603-876b-e59ae2a9529f)

Ref 4: Organization Units (OU)

In the "Secure Active Directory Deployment and Monitoring" project, the use of organizational units (OUs) is important for effectively managing the Active Directory environment. OUs allow the project owner to logically group and organize user accounts, computer accounts, and other Active Directory objects based on criteria such as department, location, or job function. This enables the application of targeted Group Policy settings and security controls to specific groups of users and systems, enhancing the overall security and manageability of the Active Directory infrastructure. The proper creation and configuration of OUs are crucial for implementing a well-structured and secure Active Directory environment as part of this project.

![image](https://github.com/user-attachments/assets/b592b62b-43f7-4d07-9a4d-4e8a7ba7233c)
![image](https://github.com/user-attachments/assets/a7297474-eac5-4876-8f0c-e2f87a68eeba)

Ref 5: Adding users to Organization Units

![image](https://github.com/user-attachments/assets/5c761b43-6f31-4849-9035-0c1cf0ae0fec)

Ref 6: Allocating Windows workstation to local domain

![image](https://github.com/user-attachments/assets/b726c242-3776-4418-bb7d-4ef5e7ed6ff2)
![image](https://github.com/user-attachments/assets/c8848c8d-fd43-43f1-9558-0669176b5fba)

Ref 7: Sysmon and Splunk Forwarder

![image](https://github.com/user-attachments/assets/c4d45c70-f51f-4e84-b1bf-0154a60c4653)

Ref 8: Creation of a new index "Endpoint"

![image](https://github.com/user-attachments/assets/b4ee3702-6ae5-452e-9022-2a3bd7b0543a)

Ref 9: Configuration of recieving port

![image](https://github.com/user-attachments/assets/ee91cfe1-5923-4e6c-84e8-0f1bc7683c65)

Ref 10: Results on the index "Endpoint"

![image](https://github.com/user-attachments/assets/a03d4faa-fcee-4352-93b1-05d420934645)
![image](https://github.com/user-attachments/assets/b41f54b2-8ab7-4449-8a03-f5ec91891e69)

Ref 11: Enable RDP on victim workstation

![image](https://github.com/user-attachments/assets/81c1da78-84bb-4f64-965f-36977a1c14c3)

Ref 12: Brute force attack on victim workstation

![image](https://github.com/user-attachments/assets/c04cf159-38cf-4cb1-8eee-8ae03e6f2df9)
![image](https://github.com/user-attachments/assets/920f073e-84ea-4f12-89a7-998e7ba22ff5)

Ref 13: Search function to view the specific point on index "Endpoint"

![image](https://github.com/user-attachments/assets/2a0c7e92-4aa1-4061-aa72-7f7a2de1ff6e)
![image](https://github.com/user-attachments/assets/b4c2de28-8a9b-48e1-bad8-d27e09234949)

Ref 14: Using ART to create a new local user and using Splunk to detect the incident

![image](https://github.com/user-attachments/assets/df4e5319-472b-40ba-88ff-75f1ef1d65d8)
![image](https://github.com/user-attachments/assets/edabde66-b481-4da7-a996-7e471f0f5a6c)
![image](https://github.com/user-attachments/assets/d1f4039e-c107-453e-82c2-4f3df3705563)
![image](https://github.com/user-attachments/assets/570ed7db-5a01-45ce-9ab5-7e8b9e4854ce)

Ref 15: Using ART to issue some commands in powershell and using Splunk to detect the incident











