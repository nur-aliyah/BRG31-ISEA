Lab 2

1) AWS Ubuntu Apache:
   - Create account in AWS: <img width="956" height="453" alt="createawsaccount" src="https://github.com/user-attachments/assets/7e07b95f-2c9f-43b6-ab11-27beb12995ae" />
   - Launch Ubuntu EC2 instance: <img width="956" height="509" alt="Screenshot 2026-11-25 191042" src="https://github.com/user-attachments/assets/ed9d9a48-673f-4eae-a637-b237b766a00c" />
   - Connect to ubuntu VM:
     //couldnt connect instance due to SSH error. try to troubleshoot the Source set to 'anywhere' then managed to open the VM
     <img width="957" height="370" alt="vmopened" src="https://github.com/user-attachments/assets/b1557a06-e23f-40e7-9099-f28ecb1faa4e" />
   - Update & upgrade Ubuntu: <img width="813" height="323" alt="Screenshot 2026-11-25 205008" src="https://github.com/user-attachments/assets/364ae56c-2cf0-4b74-8a80-30aa6acae2ba" /> <img width="926" height="326" alt="Screenshot 2026-11-25 205026" src="https://github.com/user-attachments/assets/26ae3017-1698-4618-a608-847b3b54a701" />
   - Install Apache web server: <img width="947" height="331" alt="Screenshot 2026-11-25 205726" src="https://github.com/user-attachments/assets/a18af52c-21a6-45d1-8b76-0f8ad3720070" />
   - Test Apache default landing page: <img width="959" height="482" alt="Screenshot 2026-11-25 205826" src="https://github.com/user-attachments/assets/9bbaa546-58bf-4fbe-bb99-a47d330c1c96" />

2) Learning points:
   - had difficulties launching Ubuntu VM on AWS because of the security groups configuration
   - instead of using own IP for SSH, i used 'Anywhere', then the VM connected and launched successfully
   - installing and managing Apache on AWS was manageable just by following the lab instructions
   - managed to launch the Apache test page on browser using https followed by my public ip address






