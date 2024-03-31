MISP Threat Intelligence, also known as MISP Threat Sharing, is an open-source threat intelligence platform designed to facilitate the collection, storage, distribution, and sharing of cybersecurity indicators and threats related to cybersecurity incidents and malware analysis. It is aimed at incident analysts, security and ICT professionals, and malware reversers to support their day-to-day operations by efficiently sharing structured information.

![misp-logo](https://github.com/MOUSSADOUNDA/Setup-a-Powerful-Open-Source-Threat-Intelligence-Platform-MISP/assets/129728703/225ab144-adcf-42ba-9108-c3b808e21c19)

The goal of this project is to install and configure MISP on our Ubuntu server, and then fetch data from threat intelligence feeds.

Let's start with the installation steps.
1. update the Ubuntu server
   ![misp_1](https://github.com/MOUSSADOUNDA/Setup-a-Powerful-Open-Source-Threat-Intelligence-Platform-MISP/assets/129728703/64d58dfc-41f7-414d-867c-226df96041cc)
2. Download the MISP repository
   wget --no-cache -O /tmp/INSTALL.sh https://raw.githubusercontent.com/MISP/MISP/2.4/INSTALL/INSTALL.sh
   
   ![misp_2](https://github.com/MOUSSADOUNDA/Setup-a-Powerful-Open-Source-Threat-Intelligence-Platform-MISP/assets/129728703/4170c3d1-a68d-43ba-8566-15a86b08be0f)
4. Install MISP
   bash /tmp/INSTALL.sh then bash /tmp/INSTALL.sh -A to install All
   ![misp_2_1](https://github.com/MOUSSADOUNDA/Setup-a-Powerful-Open-Source-Threat-Intelligence-Platform-MISP/assets/129728703/1fa9c9fb-ff3a-4160-ae28-1205a945b343)
   ![misp_2_2](https://github.com/MOUSSADOUNDA/Setup-a-Powerful-Open-Source-Threat-Intelligence-Platform-MISP/assets/129728703/0723b955-05fe-44f7-a250-d183d9ebd861)

   You will see a prompt to create a new user for misp or to continue with the root account. For my case, I continued with the root account
   ![misp_2_3](https://github.com/MOUSSADOUNDA/Setup-a-Powerful-Open-Source-Threat-Intelligence-Platform-MISP/assets/129728703/bc17aa07-b468-4602-99c5-42321172a73e)
 
   Finally, MISP is installed
   ![misp_2_4](https://github.com/MOUSSADOUNDA/Setup-a-Powerful-Open-Source-Threat-Intelligence-Platform-MISP/assets/129728703/ff19be54-c523-4e06-bfbd-08ca9dfdf12c)

   We can have access to MISP from the browser using our localhost IP address
   ![misp_3](https://github.com/MOUSSADOUNDA/Setup-a-Powerful-Open-Source-Threat-Intelligence-Platform-MISP/assets/129728703/2ffd6dd1-bad7-4c8c-88bf-f07a421b1a6e)

   The main interface is always empty after a new installation
   ![misp_4](https://github.com/MOUSSADOUNDA/Setup-a-Powerful-Open-Source-Threat-Intelligence-Platform-MISP/assets/129728703/67a91410-8e08-4c80-a4c8-64247cf8dcef)

   Let's have a look at the available feeds. To do so, click on the Sync Action section and click on feeds
   We can see the available feeds. Before we continue click on fetch and store feed data
   Select the feeds that you want to enable and click on Enable Selected
   ![misp_5](https://github.com/MOUSSADOUNDA/Setup-a-Powerful-Open-Source-Threat-Intelligence-Platform-MISP/assets/129728703/0a7760f0-097a-4d71-a802-acef6974a44e)
  
