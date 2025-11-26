# Onboarding Simulation Knowledge Base  

This document contains all steps performed during the onboarding simulation.



\# Device Preparation These steps were performed inside Oracle VirtualBox:



1\. Created a Windows 10 VM (50GB VDI, 4GB RAM, 2 CPUs)

2\. Attached Windows 10 ISO and installed OS

3\. Installed VirtualBox Guest Additions

4\. Ran Windows Update 

5\. Renamed device to: \*\*WIN10-EMPLOYEE-LAPTOP01\*\*



Evidence:  

\- `/Assets/Screenshots/` folder (VM settings, installer, desktop, updates)



\# Simulated Enterprise Account Setup (SIMULATED)

Because the ISO used does not support Azure AD join:



\### Simulated steps performed:

\- Opened \*\*Settings → Accounts → Access work or school\*\*

\- Attempted to “Connect work account” using:  

&nbsp; `tito@becoming.com`

\- Captured screenshot of the Connect dialog



\### Real world process :

If using Windows 10 Enterprise:

1\. User chooses \*\*“Join this device to Azure Active Directory”\*\*

2\. Device registers in \*\*Microsoft Entra ID\*\*

3\. Device auto-enrolls into \*\*Microsoft Intune\*\*

4\. Policies, apps, and configurations are pushed automatically



This documentation details the real process even though the ISO cannot perform it.



\# Productivity \& Work Tools 

Installed or opened the following:

\- Microsoft Teams (download page)

\- OneDrive Setup

\- Office.com login portal

\- Edge profile sign-in



Screenshots collected.





\# Security Configuration 

Opened and documented:

\- Windows Security dashboard  

\- Virus \& Threat Protection  

\- Firewall \& Network Protection  

\- Device Health  

\- Windows Update settings  



These simulate enterprise baselines such as:

\- Endpoint protection  

\- Firewall enforcement  

\- Patch compliance





\# Local Configuration Policies 

On Windows 10 Pro:

\- Opened `gpedit.msc`

\- Navigated to:  

&nbsp; \*Computer Configuration → Admin Templates → Windows Components → Windows Update\*

\- Enabled "Configure Automatic Updates"



On Windows 10 Home:

\- Screenshot taken showing \*\*gpedit.msc not available\*\*  

\- Explanation added about real-world device policy via Intune





\# Final Checks 

The following were validated:

\- Device runs smoothly  

\- Windows activation not required for simulation  

\- Software opens correctly  

\- Screenshots saved  

\- Device is ready for demonstration  





\# Conclusion

This KB documents both:

\- The \*\*real simulation performed\*\*

\- And the \*\*actual enterprise onboarding process\*\* used in production environments







