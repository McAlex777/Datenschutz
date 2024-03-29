**Version v1.4.1 (2023-10-01)** 

========================================================

**German/English Privacy-Script (Windows 10/11 Home/Pro):**

* Reduce Telemetry via Policy (GPO/Registry) for Windows10/11 (Home/Pro), Microsoft-Office, Edge-Chromium, Chrome, Firefox.
* Disable Telemetry-Services by Project "SiSyPHuS" (BSI).
* Disable Telemetry-Services by Services.
* Disable Telemetry-Services by Scheduled Tasks.
* Disable Telemetry-Services by Windows Firewall.
* Disable Windows CoPilot.
* Disable Cloud-Access such as OneDrive.

========================================================

**German/English Firewall-Script for Boot-Process (Windows 10/11 Home/Pro):**

* Disable telemetry services on every startup similar to the privacy script.
* Reload Windows-Firewall by manually defined configurations on every startup.
* Set dynamic Firewall rules to allow/disallow complete directorys/subdirectorys on every startup.
* Activate scheduled task for each boot-process.

========================================================

**German/English Howto for Linux-Based Gateway with database logging for internet connections.**

========================================================

**All Scripts written in Batch / Powershell.**

Scripts written/tested for german and english language.<br>
Other Windows languages will not support.

========================================================

**Description:**

The project is primarily aimed at users who want their Windows10/11 to be a cloud-free, offline system with installed applications, as it was in Windows7 times.

The Windows10/11 telemetry should be reduced as far as possible.<br> 
Several methods are used for this: Policies, service disabling, and firewall blocking.

The primary goal is a comprehensible, script-controlled conversion of the system with Microsoft board means - i.e. without external applications. A further goal is a sustainable conversion - via the standard procedures provided by Microsoft. Therefore, the primary focus is on policy configurations and the simple disabling of services.

Care was taken not to restrict the user too much with the configurations.

========================================================

**Documentations in german/english language.**

Installation-Guide__DE/EN.pdf for beginners.<br>
Detail documentations, changes, GPO-settings, howtos, and BSI documentations included.

========================================================

**DISCLAIMER:**

THIS SCRIPT IS A HOBBY PROJECT.

ALL SCRIPT CODE (*.bat, *.ps1, *.php, *.sql, *.txt) IS LICENSED TO GPL v2.0.

THIS PROJECT IS LIKE IT IS: THERE IS NO GUARANTEE OF WORKING CORRECTLY.

DOZEN SYSTEM CHANGES WILL BE MADE IN WINDOWS - SO ITS YOUR OWN RISC.

THERE ARE NO UNINSTALL ROUTINES.

CREATE FULL SYSTEMBACKUP BEFORE USE IN PRODUCTIVE ENVIRONMENT.
