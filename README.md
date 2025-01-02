# Windows-Forensic-Artifacts-Program-Execution

<h2>Description</h2>
In this Digital Forensics task, I used registry explorer to enumerate executable program locations within SYSTEM,SOFTWARE, & NTUSER.DAT hives.

<h2>Languages and Utilities Used</h2>

- <b>Registry Explorer</b>

<h2>Environments Used </h2>

- <b>Windows 10 Enterprise</b> 

<br />
<br />
In registry explorer going to NTUSER>DAT\Software\Microsoft\Windows\CurrentVersion\Explorer\UserAssist to view Windows artifact that tracks and stores information about executed GUI-based programs, including their execution count and last run time, to enhance user experience and provide valuable forensic data.

![1) UserAssist](https://github.com/user-attachments/assets/05a0695d-3412-41db-823c-891e6a5c1bab)

<br />
<br />
Went to SOFTWARE\Microsoft\Windows\CurrentVersion\Run to view programs used in the run command within the SOFTWARE hive registry key. 

![2) SOFTWAREMicrosoftWindowsCurrentVersionRun](https://github.com/user-attachments/assets/11b4821e-79a4-4608-8493-10b6009d9c32)

<br />
<br />  
Went to NTUSER.DAT\Software\Microsoft\Windows\CurrentVersion\Run to view programs used in the run command within the NTUSER.DAT registry key. 

![3) NTUSER DATSoftwareMicrosoftWindowsCurrentVersionRun](https://github.com/user-attachments/assets/b85686cc-294a-48db-bbe7-174e057ae11f)

<br />
<br />
Going to SYSTEM\CurrentControlSet\Services will Enumerates all the services installed on the system. Parameters include image path, description, display name, etc. 

![4) SYSTEMCurrentControlSetServices](https://github.com/user-attachments/assets/e70c9ae9-941e-481d-b20e-95627af4c5ba)

<br />
<br />
Going to SOFTWARE\Microsoft\Windows NT\CurrentVersion\Schedule\TaskCachewill to see stored metadata and configuration information for scheduled tasks, including task definitions, triggers, and security descriptors, which are used by the Task Scheduler service to manage and execute automated tasks on the system.

![5) SOFTWAREMicrosoftWindows NTCurrentVersionScheduleTaskCache](https://github.com/user-attachments/assets/2a16ec39-aea3-4b3a-be79-f7665b8bc6c5) 

<br />
<br />

