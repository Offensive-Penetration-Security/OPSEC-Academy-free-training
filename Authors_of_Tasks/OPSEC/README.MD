![](https://github.com/Offensive-Penetration-Security/OPSEC-Academy/blob/main/Docs/logo300-Academy.png)

## WARNING! 
- For advanced users! 

## NOTE!!! 
- You must find all problems in every task yourself, from installation to the real problem!

## MANDATORY and IMPORTANT FOR SOLVING THE TASKS!!! 
- You must describe the `Vulnerability Assessment` of every task and prove the problems for every task - `PoC`  - `presenting` exploits and apply `CVE` if it exists!
- You can use whatever `OS` you want, and [Burp Suite](https://portswigger.net/burp/releases) - Application Security Testing Software from `PortSwigger` or whatever scanner you want for solving the problems!

## How to report the solved tasks!
- Please return the solved tasks as they should, each in its own directory, thank you! 
- You must use only the `text` format to describe the problems. `HTML` is allowed!
- Where to submit your tasks: `bugb0untypropentest@gmail.com` or ask your mentor and teacher!

## YOU SHOULD KNOW!!!
- If someone sends a solved task out of this requirement, we will not check their work!
- After you finish some tasks, you must compress them into a `tar` or `zip` archive!

- - For example :

```txt
OPSEC-Academy
|
|
\ 
  Name: author of the tasks
    |
    |
    \
      Tasks: Task-01, Task-02, Task-03
```

# REQUIRED REPORT TEMPLATE!

[link](https://github.com/Offensive-Penetration-Security/OPSEC-Academy-free-training/tree/main/Authors_of_Tasks/OPSEC/report)

# How to install every LAB

- - - FOR ADVANCED USERS on Windows 8/10/11:

1. Install [XAMPP](https://www.apachefriends.org/download.html)
2. Extract the LAB in the `htdocs` directory of your XAMPP 
3. Set up a `database` and upload your .sql file
4. Find the vulnerability
5. report

- - - AUTOMATION - Linux V-ENV for `beginners`:

1. Download your V-ENV

<p align="left">
  <a href="https://www.mediafire.com/file/j4vshwia3twlssg/OPSEC-VL-VMware.7z/file">
    <img src="https://raw.githubusercontent.com/Offensive-Penetration-Security/OPSEC-Academy-free-training/refs/heads/main/Authors_of_Tasks/OPSEC/docs/VMware_Workstation_Player_Icon.png"
         alt="VMware Workstation / Player" width="100" height="100">
  </a>
  &nbsp;&nbsp;&nbsp;
  <a href="https://www.mediafire.com/file/4xv9s70l8oerksu/OPSEC-VL-OVA.7z/file">
    <img src="https://raw.githubusercontent.com/Offensive-Penetration-Security/OPSEC-Academy-free-training/refs/heads/main/Authors_of_Tasks/OPSEC/docs/VirtualBox_2024_Logo.svg.png"
         alt="VirtualBox" width="100" height="100">
  </a>
</p>

2. Deploying it using the video `How To`
3. Start the VM machine and follow the instructions `After install`

# After install

In every LAB from 1 - 5

- Going in:
```
vim /var/www/lab1/acms/initialize.php 
```
- on this line:
```
if(!defined('base_url')) define('base_url','http://localhost:8081/acms/');
```
- change
```
http://localhost:8081/acms/
```
- with your IP, for example
```
http://192.168.1.15:8081/acms/
```
- Save and exit

- Done! 

------------------------------------------------

# Video demo for XAMPP installation: 

[howto](https://www.youtube.com/watch?v=G2VEf-8nepc)

# Video demo: 

[howto](https://www.patreon.com/posts/opsec-vl-venv-142973442)

- - - OPSEC-VL machine credentials

```
user: OPSEC-VL
password: opsec
```
----------------------------------------------

# Solving of LAB 1 - SQLi - for educational purposes ONLY!

[Solving Lab1](https://www.patreon.com/posts/lab1-solving-in-143105988)

----------------------------------------------

# Exam price:

```
50$  - For colleges
150$ - Outside of colleges
```
-----------------------------------------------

***Good luck everyone*** `OPSEC`
