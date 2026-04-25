
This lab focuses on the essential first steps for securing Cisco networking hardware, specifically a 2911 router and a 2960 switch. The primary objective is to move beyond default settings by assigning unique hostnames and implementing tiered access security. You will practice configuring the legacy enable password and the more secure enable secret, observing how the Cisco IOS prioritizes the hashed secret over the plain-text password to protect privileged mode access.





The second half of the exercise demonstrates the importance of configuration privacy and persistence. By using the service password-encryption command, you will learn how to obscure clear-text passwords into Type 7 hashes within the configuration file. Finally, the lab concludes with the critical task of saving the active settings from volatile RAM to NVRAM using the copy running-config startup-config command, ensuring that all security measures remain intact after a device reboot.
