![d2550626a1c94aeebd273d43be0669c9.png](../../_resources/d2550626a1c94aeebd273d43be0669c9.png)
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>



<p align="center"><font size="6"><b>Name:</b> Full Name</font></p>
<p align="center"><font size="6"><b>Email:</b> Email Address</font></p>
<p align="center"><font size="6"><b>OSID:</b> 8000x</font></p>



<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
Copyright © 2022 Offensive Security Ltd. All rights reserved.
No part of this publication, in whole or in part, may be reproduced, copied, transferred or any other right reserved to its copyright owner, including photocopying and all other copying, any transfer or transmission using any network or other means of communication, any broadcast for distant learning, in any form or by any means such as any information storage, transmission or retrieval system, without prior written permission from Offensive Security.


<div style="page-break-after: always;"></div>


# Contents

- 1.0 Offensive-Security OSEP Exam Documentation
   - 1.1 Objective
   - 1.2 Requirements
- 2 High-Level Summary
   - 2.1 Chain of Attack Table
   - 2.2 Proof Table
- 3 Hostname 192.168.x.x Flag 1
	- 3.1 NMAP Scan
	- 3.2 Compromised Steps
	- 3.3 local.txt
	- 3.4 Privesc
	- 3.5 Proof
	- 3.6 Post-Exploitation Steps
- 4 Hostname 192.168.x.x Flag 2
	- 4.1 NMAP Scan
	- 4.2 Compromised Steps
	- 4.3 local.txt
	- 4.4 Privesc
	- 4.5 Proof
	- 4.6 Post-Exploitation Steps
- 5 Hostname 192.168.x.x Flag 3
	- 5.1 NMAP Scan
	- 5.2 Compromised Steps
	- 5.3 local.txt
	- 5.4 Privesc
	- 5.5 Proof
	- 5.7 Post-Exploitation Steps
- 6 Hostname 192.168.x.x Flag 4
	- 6.1 NMAP Scan
	- 6.2 Compromised Steps
	- 6.3 local.txt
	- 6.4 Privesc
	- 6.5 Proof
	- 6.6 Post-Exploitation Steps
- 7 Hostname 192.168.x.x Flag 5
	- 7.1 NMAP Scan
	- 7.2 Compromised Steps
	- 7.3 local.txt
	- 7.4 Privesc
	- 7.5 Proof
	- 7.6 Post-Exploitation Steps

    
<div style="page-break-after: always;"></div>


# 1.0 Offensive-Security OSEP Exam Documentation
The Offensive Security OSEP exam documentation contains all efforts that were conducted in order to pass the Offensive Security Experienced Penetration Tester exam. This report will be graded from a standpoint of correctness and fullness to all aspects of the exam. The purpose of this report is to ensure that the student has the technical knowledge required to pass the qualifi-cations for the Offensive Security Experienced Penetration Tester certification.

## 1.1 Objective
The objective of this assessment is to perform an external penetration test against the Offensive Security Exam network. The student is tasked with following methodical approach in obtaining access to the objective goals. This test should simulate an actual penetration test and how you would start from beginning to end, including enumeration and post-exploitation. The exam report is not meant to be a penetration test report, but rather a writeup of the steps taken to locate, enumerate and compromise the network.
Enumeration and post-exploitation actions that lead to subsequent attacks with successful com-promises should be included in the report.
An example page has already been created for you at the latter portions of this document that should give you ample information on what is expected to pass this exam. Use the sample report as a guideline to get you through the reporting.

## 1.2 Requirements
The student will be required to fill out this exam documentation fully and to include the following sections:
•	High level summery of findings, including the depth of compromise.
•	Methodology walkthrough and detailed outline of steps taken including enumeration.
•	Each finding with included screenshots, walkthrough, sample code or reference.
•	Screenshot of any local.txt, proof.txt or secret.txt.


<div style="page-break-after: always;"></div>


# 2.0 High-Level Summary
A brief description of the attack chain with machine names, including the depth of compromise should be included here.

## 2.1 Chain of Attack Table

Server IP Address | Hostname | Compromised | Low-Privilege User | High-Privilege User
------------------|----------|--------------|-------|---------
192.168.x.x    | Hostname   | Yes 	| user | Administrator
192.168.x.x     | Hostname   | Yes | N/A | Administrator
192.168.x.x    | Hostname  		| Yes | username | root
192.168.x.x    | Hostname  		| Yes | username | username
192.168.x.x    | Hostname  		| Yes | username | username
192.168.x.x    | Hostname  		| Yes | username | Username


## 2.2 Proof Table

local.txt and proof.txt 

HostName | Local |  Proof
--------------------------|------------------------|--------------------------------
Hostname |local key | proof key
Hostname | N/A | Proof Key
Hostname |N/A | Proof Key
Hostname |N/A | Proof Key
Hostname |N/A | Proof Key
Hostname |N/A | Proof Key



<div style="page-break-after: always;"></div>


# 3.0  Hostname 192.168.x.x Flag 1

## 3.1 NMAP Scan


## 3.2 Compromised Steps

## 3.3 local.txt

## 3.4 Privesc

## 3.5 proof.txt

## 3.6 Post-Exploitation Steps


<div style="page-break-after: always;"></div>


# 4.0  Hostname 192.168.x.x Flag 2

## 4.1 NMAP Scan


## 4.2 Compromised Steps

## 4.3 local.txt

## 4.4 Privesc

## 4.5 proof.txt

## 4.6 Post-Exploitation Steps

<div style="page-break-after: always;"></div>



# 5.0  Hostname 192.168.x.x Flag 3

## 5.1 NMAP Scan

## 5.2 Compromised Steps

## 5.3 local.txt

## 5.4 Privesc

## 5.5 proof.txt

## 5.6 Post-Exploitation Steps

<div style="page-break-after: always;"></div>




# 6.0  Hostname 192.168.x.x Flag 4

## 6.1 NMAP Scan


## 6.2 Compromised Steps

## 6.3 local.txt

## 6.4 Privesc

## 6.5 proof.txt

## 6.6 Post-Exploitation Steps
<div style="page-break-after: always;"></div>


# 7.0  Hostname 192.168.x.x Flag 5

## 7.1 NMAP Scan


## 7.2 Compromised Steps

## 7.3 local.txt

## 7.4 Privesc

## 7.5 proof.txt

## 7.6 Post-Exploitation Steps

<div style="page-break-after: always;"></div>