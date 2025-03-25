# EIGRP-Lab


</p>

<h1>EIGRP Configuration </h1>





<h2>Environments and Technologies Used</h2>

- VMware
- Cisco SimuRack
- Putty
- Cisco Routers

<h2>Operating Systems Used </h2>

- Cisco ios


<h2>How to get Started</h2>

- Open VMware
- Start virtual machine
- Browse SimuRack
- Open a Rack in SimuRack

<h2>Deployment and Configuration Steps</h2>

![image](https://github.com/user-attachments/assets/dea8a398-9581-4af8-b914-0a9a0e5d6545)

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


![image](https://github.com/user-attachments/assets/7124ddc0-41f3-4a0b-b55d-77de96c82eb6)

![image](https://github.com/user-attachments/assets/0e8c0b54-62ce-40d3-bccf-c42ac1dd72ea)

</p>
<p>
- apply md5 authentication from r3 to r9
  <p>
    - observe changes
</p>
<br />


![image](https://github.com/user-attachments/assets/a4f5016e-9e8d-4b61-8c3a-7b2688107622)

</p>
<p>
- shut down the link from r3- r6
  <p>
    - observe changes
</p>
<br />


![image](https://github.com/user-attachments/assets/a71161a6-7171-49a2-9d96-05da16a150b5)

</p>
<p>
- apply md5 from r9 to r3
  <p> 
    - observe changes
    <p>
      - turn back on the link from r3 to r6
</p>
<br />



![image](https://github.com/user-attachments/assets/6b2e617e-e027-4d66-907b-177ed82d1225)
![image](https://github.com/user-attachments/assets/c809670f-3161-41f2-8c22-49eaecfa3328)
![image](https://github.com/user-attachments/assets/ee6fc0a8-fd4b-48f0-851c-8d9954b67c11)
![image](https://github.com/user-attachments/assets/50fdc4f5-a270-4d0b-9906-ac56d4ac64ff)

</p>
<p>
- apply md5 from r3 to r6 and r6 to r9
  <p>
    - observe changes
</p>
<br />


![image](https://github.com/user-attachments/assets/a9ea8f90-38a5-4bde-8cc4-d21bf8b88870)
![image](https://github.com/user-attachments/assets/2fe3cb1b-685f-4280-a864-58ecd71b97c9)

</p>
<p>
- apply md5 back
  <p>
    - observe changes
</p>
<br />


![image](https://github.com/user-attachments/assets/1a6cf336-b8bc-4688-b489-aa28edbc3eed)
![image](https://github.com/user-attachments/assets/0f1f87ee-bf25-4bb4-ad1d-32af6f193b66)

</p>
<p>
-add a metric of 80,000,000 to all outbound links from r9 to r6
  <p>
    - observe changes
</p>
<br />


![image](https://github.com/user-attachments/assets/900f5bc7-a40c-48c6-916e-4b8647c0d9ac)

</p>
<p>
- add a metric of 80,000,000 from r6 to r9
  <p>
    - observe changes
</p>
<br />


![image](https://github.com/user-attachments/assets/9ec6317b-ba3e-48a9-b2bb-6ff3cf3f84e0)
![image](https://github.com/user-attachments/assets/54060f53-9264-40e9-b824-9ccf70189e4a)

</p>
<p>
- add a new network on a new interface on r6
<p>
  - advertise into EIGRP 120
  <p>
  - observe changes
</p>
<br />


![image](https://github.com/user-attachments/assets/3b881b58-3951-47ea-a9f9-c583f79fac00)

</p>
<p>
- redistribute EIGRP 120
  <p>
    - observe changes
</p>
<br />




<p>
This lab was to meant for me to get experience configuring EIGRP. Make sure to check out the PowerPoint presentation made for this. Thank you.


