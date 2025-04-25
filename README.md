# Compromising-windows-using-Metasploit
To Compromise the windows using metasploit.
# Aim :
To Compromise the windows using metasploit.

# Design Steps: 
1. Install kali linux either in partition or virtual box or in live mode.
2. Investigate on the various categories of tools as follows.
3. Open terminal and try execute kali linux commands.

# Execution Steps and it's Output:
## Step1: Identify the Attacker's IP Address
Determine the IP address of the attacker's system.

<img width="400" alt="image" src="https://github.com/user-attachments/assets/de99bccb-413f-4481-bf4f-6e006b818de7" />

## Step2:Launch the Metasploit Console
Invoke the msfconsole

<img width="400" alt="image" src="https://github.com/user-attachments/assets/d7269e26-63a0-480d-8e4b-ac07e26b8d5a" />

## Step3:Generate Payload Using msfvenom
Execute the following command to generate a Windows Meterpreter reverse shell payload.exe 

<img width="400" alt="image" src="https://github.com/user-attachments/assets/9c3a01d5-db13-4a8f-a634-2189e9733a51" />

## Step4: SetUp an HTTP Server
Once the payload file is created, navigate to the hime directory.Right-click and select "open terminal here"

<img width="400" alt="image" src="https://github.com/user-attachments/assets/b1151011-6311-4efc-ac38-2d4768e28f05" />


Run the Python command to establish an HTTP server  for file distribution.

<img width="400" alt="image" src="https://github.com/user-attachments/assets/7a758e60-9319-4047-ba95-d3e3feef67ef" />

## Step5: Distribute the Payload
Share the .exe file with the target system via any medium or the HTTP server. Once the victim downloads and executes the file,the exploit is triggered.

<img width="400" alt="image" src="https://github.com/user-attachments/assets/90c37a99-245d-42a4-8211-9dbaed68f017" />

## Step6: Establish a Connection
On Kali linux, reopen the terminal and invoke "msfconsole".Follow the necessary steps to establish a connection with the victim's device.
<img width="400" alt="image" src="https://github.com/user-attachments/assets/123debe7-9cd0-4ccd-897c-e064ed3cfa7d" />

## Step7:List Commands
Use the help command to list available operations.

<img width="400" alt="image" src="https://github.com/user-attachments/assets/6e31ca21-f0f7-4ab9-b4ab-887d5a77dae0" />





## Step8:
For example,the "key_scan" command captures the victim's screen and saves it in the attacker's home directory.

<img width="400" alt="image" src="https://github.com/user-attachments/assets/5dcf83ce-110f-4e93-9d0f-e95b0af18be1" />





## RESULT:
The Metasploit framework is  used to compromise windows and is examined successfully.
