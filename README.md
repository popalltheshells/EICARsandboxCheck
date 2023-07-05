# EICARsandboxCheck
In a penetration test, specifically while testing an upload functionality - it is important to see if the application server prevents users from uploading malicious files especially if all files are stored (and can be downloaded by others). This project contains all the EICAR files needed to test if a web application has a Virus sandboxing mechanism. Each eicar file has been modified to bypass client & server side file-type restrictions. 

## Proof of concept
I've confirmed that each modified eicar test files are still flagged as "malicious" on VT. Meaning that if the web application doesn't prevent you from uploading the file - it does not have an AV sandboxing capability.

![image](https://github.com/popalltheshells/EICARsandboxCheck/assets/6753178/42862c3f-0799-4e3b-9c0f-e3fe5579be9e)
