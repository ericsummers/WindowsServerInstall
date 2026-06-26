<h1>Windows Server 2025 Install</h1>

<h2>Description</h2>
Project consists of configuring and creating a virtual machine (VM) using Oracle VirtualBox software, installing Windows Server 2025 DataCenter Eval operating system, and configuring any initial post-innstallation tasks through Windows Server Manager.
<br />


<h2>Utilities Used</h2>

- <b>Oracle VirtualBox Manager</b> 

<h2>Environments Used </h2>

- <b>Windows Servevr 2025 DataCenter Evaluation Edition (Desktop Experience)</b>

<h2>PART 1: Creating the Virtual Machine (VM)</h2>

1. Launch Oracle VirtualBox Manager
2. Click "New" to Configure VM:<br/>
<img width="838" height="540" alt="Screenshot 2026-06-21 at 3 12 33 PM" src="https://github.com/user-attachments/assets/a9a8e3b8-d205-4a10-a1c7-dc90927683c2" />
<br />
<br />
3. Name the VM (Corp-DC1):<br>
<img width="978" height="482" alt="Screenshot 2026-06-24 at 8 23 25 PM" src="https://github.com/user-attachments/assets/1f491abe-6670-4e4f-9f20-ff947f5011cb" />
<br />
<br />
4. Select a Location to Save the VM File:<br>
<img width="973" height="485" alt="Screenshot 2026-06-24 at 8 23 57 PM" src="https://github.com/user-attachments/assets/be02554b-28c9-47d4-89d7-269c9e2b8064" />
<br />
<br />
5. Mount the Downloaded ISO file of Windows Server 2025 and Configure:</br>
<img width="975" height="514" alt="Screenshot 2026-06-24 at 8 27 45 PM" src="https://github.com/user-attachments/assets/556dc7f8-961b-43eb-8315-b674e56cdf96" />
<br />
<br />
6. Specify Virtual Hardware Resources of VM:<br/>
<img width="978" height="516" alt="Screenshot 2026-06-24 at 8 34 17 PM" src="https://github.com/user-attachments/assets/43a5450f-e5f0-4fa1-9b5d-9a973f2ce32b" />
<br />
<br />
7. Confirm the Configuration and Click "Finish":<br/>
<img width="977" height="493" alt="Screenshot 2026-06-24 at 8 38 34 PM" src="https://github.com/user-attachments/assets/0441adac-588e-457b-b8b1-2471914502f3" />
<br />
<br />

<h2>PART 2: Starting the Virtual Machine</h2>

8. Right-Click the VM (Corp-DC1) in VirtualBox Manager and Select "Start" > "Start With GUI":</br>
<img width="839" height="542" alt="Screenshot 2026-06-24 at 8 43 58 PM" src="https://github.com/user-attachments/assets/4759770f-66f7-4331-a44e-ffc8f4aa5310" />
<br />
<br />

<h2>PART 3: Install the Operating System (Windows Server 2025)</h2>

9. Select a Language and Click "Next":</br>
<img width="724" height="753" alt="Screenshot 2026-06-24 at 8 56 22 PM" src="https://github.com/user-attachments/assets/1fff80cc-06db-4490-a69c-4832fc832403" />
<br />
<br />

10. Select a Keyboard Layout and Click "Next":</br>
<img width="720" height="755" alt="Screenshot 2026-06-24 at 8 57 05 PM" src="https://github.com/user-attachments/assets/e90598e3-9304-46ef-bf16-d66a60199172" />
<br />
<br />

11. We Want a Clean Install. Select "Install Windows Server, Check the Box to Agree, and Click "Next":</br>
<img width="722" height="755" alt="Screenshot 2026-06-24 at 8 59 46 PM" src="https://github.com/user-attachments/assets/f169a4d6-e056-4193-8c26-d4e2000de29f" />
<br />
<br />

12. Select the OS Version: :Windows Server 2025 Datacenter Evaluation (Desktop Experience), then Click "Next":</br>
<img width="717" height="755" alt="Screenshot 2026-06-24 at 9 01 51 PM" src="https://github.com/user-attachments/assets/68470fec-3069-4e46-9871-c1f985a3da28" />
<br />
<br />

13. Accept the License Terms Agreement:</br>
<img width="727" height="760" alt="Screenshot 2026-06-24 at 9 06 31 PM" src="https://github.com/user-attachments/assets/3c4e07b6-0eda-4ad3-ba80-03e7144f5461" />
<br />
<br />

14. Choose the Install Location of the Operating System (the VHD we created in PART 1. Select "Next":</br>
<img width="726" height="758" alt="Screenshot 2026-06-24 at 9 08 58 PM" src="https://github.com/user-attachments/assets/52bade53-8154-4b55-aa9d-a453c1436d51" />
<br />
<br />

15. Confirm the Install by Clicking "Install":</br>
<img width="720" height="756" alt="Screenshot 2026-06-24 at 9 11 35 PM" src="https://github.com/user-attachments/assets/ac3acc31-7ba7-4dc7-901c-547f2ca16b7c" />
<br />
<br />


16. Once Installed, Create an Administrator Account Password for Local Administrator Account and Click "Finish":</br>
<img width="798" height="671" alt="Screenshot 2026-06-24 at 9 29 58 PM" src="https://github.com/user-attachments/assets/73798df0-9f62-4b20-bb0e-dc5e0599c594" />
<br />
<br />

17. Sign in With Administrator Account Password Created in Step 16:</br>
<img width="512" height="548" alt="Screenshot 2026-06-24 at 9 34 28 PM" src="https://github.com/user-attachments/assets/4fc65077-e86d-4ba1-af18-957b77870469" />
<br />
<br />

18. Accept the Microsoft Prompt:</br>
<img width="520" height="547" alt="Screenshot 2026-06-24 at 9 46 35 PM" src="https://github.com/user-attachments/assets/9678f949-8ad9-4c50-af98-449eee77c212" />
<br />
<br />

20. Windows Server 2025 is Now Installed on Corp-DC1 using Oracle VirtualBox Hypervisor:
<img width="508" height="535" alt="Screenshot 2026-06-24 at 9 51 09 PM" src="https://github.com/user-attachments/assets/ac636178-2da0-46b7-9a98-f86c2228429f" />
<br />
<br />

<h2>PART 4: Post-Installation Tasks</h2>

<h3>Check Activation Status and Rename Computer</h3>

21. In the Server Manager Program, "Select Local Server":</br>
22. Check the "Product ID" to Verify Windows is Activated</br>
<img width="953" height="812" alt="Screenshot 2026-06-25 at 7 34 16 PM" src="https://github.com/user-attachments/assets/a718dcbb-f3e4-4c49-976d-8cce2075c238" />
<br />
<br />

22. In the System Properties Box, Click "Change":</br>
<img width="948" height="810" alt="Screenshot 2026-06-25 at 7 37 16 PM" src="https://github.com/user-attachments/assets/4d6bdb79-a11e-46f8-acb1-e6db94ce8add" />
<br />
<br />

23. Change the name to CORP-DC1 and Click "OK" - **RESTART IS REQUIRED**:</br>
<img width="1021" height="820" alt="Screenshot 2026-06-25 at 7 41 12 PM" src="https://github.com/user-attachments/assets/144a2966-41bd-4785-87d8-58b1a9c42351" />
<br />
<br />
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
