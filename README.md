# Resolving-the-Trust-Relationship-Error-Step-by-Step-Guide-
The trust relationship error means a domain-joined computer can no longer prove its identity to a domain controller (DC). Every domain member has a computer account with a password that changes automatically (every 30 days by default).If the computer and Active Directory disagree on that password, the "securing channel" breaks and domain logons fail 
<img width="1050" height="612" alt="image" src="https://github.com/user-attachments/assets/af9a3f5c-a0d2-421d-8303-78158ec679de" />
This is how Error A appears on the logon screen after a user presses Ctrl+Alt+Delete and tries a domain account. 
Error B: Alternate logon message 
Windows The security database on the server does not have a computer account for this workstation trust relationship. [OK] 
1. Step for troubleshoot step Disconnected PC from Domain 
 
   username =.\admin 
   Password = your credentials  
<img width="975" height="354" alt="image" src="https://github.com/user-attachments/assets/78b318e0-74b5-4a5d-9f4b-9fdf5028dd11" />
After checking Network connectivity through CMD ipconfig /all 
  <img width="975" height="480" alt="image" src="https://github.com/user-attachments/assets/01d9c210-dd4f-4b20-a539-e011b6ce1a82" />
Conform to ping Domian Name reach or not?
<img width="975" height="360" alt="image" src="https://github.com/user-attachments/assets/4252bf30-4eee-4f75-addb-167f97e20362" />
Disconnected domain from PC
<img width="503" height="434" alt="image" src="https://github.com/user-attachments/assets/ab2051a8-0eb3-4c96-adfb-493fb093bd92" />
After disconnect domain from PC Need to restart 
Now pc disconnected from domain 
<img width="975" height="355" alt="image" src="https://github.com/user-attachments/assets/2d3fcf9e-ad80-4158-ac08-9d80e9336b29" />
Again, connect Domain to pc through sysdm.cpl
<img width="975" height="341" alt="image" src="https://github.com/user-attachments/assets/e4674049-7799-4531-88db-779445987782" />
After connecting domain need to restart Now check whether it work or not?
<img width="975" height="690" alt="image" src="https://github.com/user-attachments/assets/d7d189ca-8f18-44c4-be47-4fd2bf5b8286" />

