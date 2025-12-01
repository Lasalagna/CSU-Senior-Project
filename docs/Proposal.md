Senior Project Proposal SCAP STIG Viewer and Hardening
===================================================

**Student Name(s)**: Joshua Menard   
**Degree and Major**: B.S. in Cybersecurity, Joshua Menard  
**Project Advisor Name**: Michael O'Neill (Joshua Menard)  
**Expected Graduation Date**: May 2027


Problem Statement
-----------------

The Charleston Southern Cybersecurity team lacks a repository of code that can be used to professionally harden a network through the SCAP (Security Compliance Automation Protocol) checking tool; to allow cyber team members a way to successfully harden a system in a competition to better their knowledge.


The Charleston Southern cyber team does not have a repository with functional code. The problem with this is cyber team members walk into competitions unprepared with other teams from school such as the U.S Naval Academy or the College of Charleston having up to date repositories for code. In conversation with previous presidents and members of the cyber team, they stated there was never a well thought out repository of code for the CSU cyber team. I propose the creation of a Github repository with code to harden both Windows and Linux systems while staying compliant with the Department of Defense’s SCAP compliance checker also known as SCAP. The reason for this solution is SCAP is an effective way to harden systems. The benefits are that the cyber team has a functional storage of code to run during competitions. This creation of a Github repository will allow for the cybersecurity team to functionally compete in tournaments and get a better position than 5th place in PCDC or last place in SECCDC.



Project Description
-------------------


A Github repository of code to harden a Windows and a Linux system while being compliant to SCAP.



Proposed Implementation Language(s) 
-----------------------------------

I would prefer powershell for Windows as it is universal for all windows systems including Windows 10, 11 and Windows Servers 2019. Linux I would like to use Bash if at all possible as is universal for all Linux systems.



Libraries, Packages, Development Kits, etc., to be used in the proposed implementation language(s)
--------------------------------------------------------------------------------------------------

Not sure yet due to syntax of both languages as well as compatibility.


Additional Software/Equipment Needed
------------------------------------

A Windows and Linux machine is required for the completion of this project. (Given through RustDesk in the CSCI network).

Alternative Solutions and Rationale 🔍
--------------------------------------

> **Purpose**: Describe at least two alternative solutions or approaches to your project. Compare these with your chosen solution based on relevant criteria (e.g., feasibility, scalability, cost, performance, usability). Explain why you selected your final approach.

### Alternative 1
- **Description**:  
  In case Linux is not cooperative for SCAP I will fully harden Windows systems and include more than just the operating system hardening, I will harden Firewall rules, Databases in which they are applied, and Microsoft Defender.
- **Pros**:  
  -Windows would be fully hardened
  -Databases following the Windows Domain Controller would be fully hardened in accordance to DoD standard.
- **Cons**:  
  - Linux will not be hardened at all leaving a "vulnerable" system in the network.
  - I personally would feel bad for not being able to cover both operating systems.

### Alternative 2
- **Description**:  
  If SCAP did not work correctly, I would use CIS which is another STIG viewer/checklist like SCAP instead.
- **Pros**:  
  - The integrity of the project stays the same.
- **Cons**:  
  - The system(s) will not be hardened to a DoD standard.

### Chosen Solution and Rationale
- **Chosen Solution**:  
  I chose to continue with SCAP as it is easier to work with for me as well as the DoD standard is something I have been interested in and how they operate and harden their networks.
- **Rationale**:  
  CIS is less in depth vs SCAP while CIS is easier to download and look at. SCAP gives me the effect that I want for the system which would be to harden the system in accordance to DoD policy and gives the cybersecurity team at CSU a way to move forward for their competitions as the world changes in the blink of an eye.

> 💡 *Tip: Consider using a comparison table to evaluate trade-offs across multiple criteria such as feasibility, performance, scalability, cost, and usability.*


Personal Motivation
-------------------

Senior year of High School my team got 3rd place in the Palmetto Cyber Defense Competition (PCDC). We could have scored higher if we had a printed out list of code that could help secure our systems faster so this will be my motivation to hopefully improve the Cyber team’s code repository and lead them to a victory over the Naval Academy.

Outline of Future Research Efforts
----------------------------------

Software development into an application that will run segments of my code to harden a system. If all dreams come true, the SCAP tool will scan and show what is wrong with the system and my tool will come in and execute sections of code to fix what is wrong with said system while keeping everything in the blue untampered with.

Schedule 📅
-----------

> Update the dates and add your tasks by replacing the examples. Remove this note.

*   Spring 2025 - CSCI 497
Requirements draft will be done by November 1st, 2025
Completed Requirements will be done by November 16th, 2025.
Construction will begin November 17th, 2025 at the latest with preliminary tests and scans done prior.
Full construction will begin post Thanksgiving break December 1st, 2025.
Results should be seen by January 23rd, 2026. 
(New Google Slides stating what SCAP found and what can be fixed).
 

*   Summer 2025/26 - Independent/Optional Project Work
    -   June 1 -

*   Fall 2026/27 - CSCI 498
    -   Ocber 20 - 
    -   October 27 - 
    -   November 3 - 
    -   November 10 - 
    -   November 17 - 
    -   November 20 - 

*   Spring 2027 - CSCI 499 (more details will be added here once you are closer)
    -   Weeks 1-4 - Implement test plan
    -   Week 5 - Evaluate test results
    -   Week 6-10 - Apply updates and bug fixes based on the results
    -   Week 8 - Complete the first 4 chapters of the defense documentation.
    -   Add the rest…


References 📚
-------------

> List any references you cited in this proposal.
