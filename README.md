# DNS-unreachable-web-site

DNS troubleshooting steps


The tools used to identify the problem were 
•	Nslookup
•	Ping
•	Microsoft Server dns manager.

Troubleshooting steps

•	I used nslookup to find the dns server IP Address
•	Once the WGU IP address was identified I compared it by using nslookup with the euronews.com site. Which has an IP of 52.209.241.99

•	After I identified the issue and IP addresses.

•	I checked the DMZ_server_3 to compare IP information  

•	Once I logged into the server, I went to the DNS management tool, where I found WGU.edu listed under the forward lookup zone.

•	To resolve the issue, I deleted the wgu.edu from the forward lookup zone within Microsoft server DNS manager.

•	I used Firefox  to view www. wgu.com.


 
 
 
 
 

 

 

 
 <img width="624" height="436" alt="Picture2" src="https://github.com/user-attachments/assets/2738117d-8f71-47c4-9886-45ffa4d4ee80" />

 

<img width="624" height="323" alt="Picture3" src="https://github.com/user-attachments/assets/0f7cefc7-8d2a-4340-9d8d-615d84daaa48" />


 
<img width="624" height="327" alt="Picture4" src="https://github.com/user-attachments/assets/5692ad3c-580b-48f4-9664-fa813f6cbd77" />

<img width="624" height="394" alt="Picture5" src="https://github.com/user-attachments/assets/e1d08c67-8479-4b71-99d6-4041e7a5ab67" />


<img width="624" height="340" alt="Picture6" src="https://github.com/user-attachments/assets/4d64e8d0-4e11-4dde-9b3c-0100706ef5e7" />

<img width="624" height="431" alt="Picture7" src="https://github.com/user-attachments/assets/26f61115-dde7-490e-91de-1b144a44079f" />
www.wgu.edu is being forwarded to this IP address 10.10.20.2
 


<img width="624" height="450" alt="Picture8" src="https://github.com/user-attachments/assets/ebec4b81-8e4c-435e-8845-ebe9b2df100a" />

<img width="624" height="446" alt="Picture9" src="https://github.com/user-attachments/assets/a472bda7-d38f-4771-8104-83d64cdc3b87" />


<img width="624" height="392" alt="Picture10" src="https://github.com/user-attachments/assets/cb4bde5e-1444-4d61-89f9-a5afe61c0b5b" />

