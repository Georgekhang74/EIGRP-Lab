# EIGRP-Lab


</p>

<h1>EIGRP Configuration </h1>





<h2>Environments and Technologies Used</h2>

- VMware
- Cisco SimuRack
- Putty
- Cisco Routers

<h2>Operating Systems Used </h2>

- Cisco CLI


<h2>How to get Started</h2>

- Open VMware
- Start virtual machine
- Browse SimuRack
- Open a Rack in SimuRack

<h2>Deployment and Configuration Steps</h2>

![image](https://github.com/user-attachments/assets/dea8a398-9581-4af8-b914-0a9a0e5d6545)
Steps"/>
</p>
<p>
- Topology overview 
  <p></p>
    - Configure the IP Addesses and EIGRP 
</p>
<br />

![image](https://github.com/user-attachments/assets/c1bae41d-249e-4f3b-adc7-c60d3b6ddec8)

![image](https://github.com/user-attachments/assets/b0bc8654-1323-4f12-94cc-e93d753aaffe)
![image](https://github.com/user-attachments/assets/2794af14-552f-4bd7-bbf9-83047de4a1c3)

</p>
<p>
- change the bandwidth from r3 - r9 to 56
  <p>
    - change the banwidth from r3-r6 to 768 
    <p>
      - change the link from r6-r9 to 1024
      <p>
        - observe changes
</p>
<br />

![image](https://github.com/user-attachments/assets/05a165f6-054b-409d-9412-d73a5da6815a)

</p>
<p>
- apply static stub to r1
  <p>
    - observe changes
</p>
<br />

![image](https://github.com/user-attachments/assets/5aecf48b-7578-47f9-bc16-dbe2fdd79baf)

</p>
<p>
- apply redistributed stub to r4
  <p>
    - observe changes
</p>
<br />


![image](https://github.com/user-attachments/assets/0e58eb2b-3fc5-45cf-ab51-0024162df049)

</p>
<p>
-apply summary stub to r7
    <p>
      - observe changes
</p>
<br />



![image](https://github.com/user-attachments/assets/80e81036-5e2f-4e9e-92ef-6b4a60428589)

</p>
<p>
- create a new interface in r7 and dont advertise it into EIGRP   
  <p>
    - observe changes
</p>
<br />


![image](https://github.com/user-attachments/assets/ad240e4c-7830-41e4-9ae4-05b19487187e)

</p>
<p>
- make it reachable with a default route 
  <p>
    - observe changes
</p>
<br />


![image](https://github.com/user-attachments/assets/966427ae-6ddf-4697-9e55-63544cf63b2e)

</p>
<p>
- create a new interface on r1 and dont advertise into EIGRP
  <p>
    - observe changes
</p>
<br />


![image](https://github.com/user-attachments/assets/f10caed3-7478-48fa-bd76-e934be35066a)

</p>
<p>
- create a default route for it
  <p>
    - observe changes
</p>
<br />


![image](https://github.com/user-attachments/assets/3e91d46a-f8da-433b-bd02-faf9e3da04e5)

</p>
<p>
- shut down the link from r8 to r7 
  <p>
    - observe changes
</p>
<br />


![image](https://github.com/user-attachments/assets/58c05157-dea6-4728-b2c1-6770e3c8024d)


</p>
<p>
- summarize r4, r5, r6 lan to be advertised to r3 and r9
  <p>
    - observe changes
</p>
<br />


<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />


<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />


<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />


<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />


<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />


<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />


<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />


<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />


<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />


<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

