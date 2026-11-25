Lab 3

1) Create a DuckDNS Account:
   - Create subdomain: <img width="956" height="485" alt="Screenshot 2026-11-25 211337" src="https://github.com/user-attachments/assets/6ce9e99b-8309-45ee-9c10-544598c4ab73" />
   - Configure Dynamic DNS: <img width="956" height="374" alt="image" src="https://github.com/user-attachments/assets/f6282842-957f-4332-a5fa-157a95766927" />
   - Install a web server: <img width="958" height="374" alt="image" src="https://github.com/user-attachments/assets/0d069579-b044-49a6-911b-b96cdffbb9c7" />
   - Point domain to server: <img width="955" height="477" alt="image" src="https://github.com/user-attachments/assets/4c3910cb-8f1a-4e65-88dc-acea9a124f85" /> <img width="956" height="368" alt="image" src="https://github.com/user-attachments/assets/852c2269-a170-40f6-a959-6b3dbdd1b49c" />
   - Open firewall ports: <img width="957" height="371" alt="image" src="https://github.com/user-attachments/assets/2778efba-6a67-4a66-8f93-3dcfcdb4b824" />
   - Obtain Free SSL Certificate (Let's Encrypt): <img width="958" height="383" alt="image" src="https://github.com/user-attachments/assets/1cafa8fb-4c1e-4c81-be9c-b469cc43f014" /> <img width="958" height="379" alt="image" src="https://github.com/user-attachments/assets/5af5e620-a037-417d-b4cc-aedf124c7f35" />
   - Test HTTPS: <img width="959" height="484" alt="image" src="https://github.com/user-attachments/assets/b03c25df-9bc0-40f4-a54b-afd58c136cd2" />
   -  Verify Certificate: <img width="955" height="369" alt="image" src="https://github.com/user-attachments/assets/11979461-b263-47fa-8588-b71d653a8de3" />
    – Auto-Renew SSL: <img width="958" height="339" alt="image" src="https://github.com/user-attachments/assets/3b5a3e40-e0da-49d2-8a4c-9c94e009e943" />
    
2) Learning points:
   - Domain Name System (DNS) are human friendly hostnames translated from numeric IP addresses so that a device knows where to connect. For example, when look up nuraliyah.duckdns.org, DNS resolves it server's IP 52.63.84.181 and it will keep mapping updated if a dynamic public IP changes
   - domain name is a readable text address used to identify a location or resource on the internet such as nuraliyah.duckdns.org instead of memorizing a raw IP address like 52.63.84.181
   - Secure Sockets Layer (SSL) and its modern successor Transport Layer Security (TLS) are cryptographic protocols that secure communication over a network. They use digital certificates and encryption keys to verify the server's identity, keep data private in transit and detect tampering.
   - HTTPS runs HTTP inside an encrypted TLS connection, protecting sensitive data like logins, tokens or form inputs, preventing tampering, and establishing trust in modern browsers.
   - Let's Encrypt is a free, automated Certificate Authority (CA) that issues TLS/SSL certificates so websites can enable HTTPS without paying for a commercial certificate. Tools like certbot automate obtaining and renewing those certificates (typically valid for 90 days) for web servers like Nginx.





