# Implementing PfSense Firewall to Home Network 
For this project I will use this mini computer to create a few open-sourced security controls that I can apply to my home network.
![Snag_1e253e4](https://github.com/HPastoral/AlienVault-HomeSIEM/assets/135756003/172f8429-057f-4206-8022-242759ec0045)

(Mini PC Intel N5095 2.9GHz, Expandable 8GB SODIMM 256GB SSD Dual LAN Windows 11 Pro, Mini Desktop Computers 4K@60Hz Triple Display, Gigabit Ethernet x2 Small PC Computer for Home Business Industry)

# Implementation:
pfSense is a powerful open-source firewall software that can be used to enhance the security and control of your home network. It offers advanced features and functionalities typically found in commercial firewalls, making it a popular choice for both small-scale and enterprise-level deployments.
![image](https://github.com/HPastoral/PfSense-Firewall/assets/135756003/bb47d70b-804a-4784-89fb-203b3c09ffc7)

# Application to a Home Network:

By integrating pfSense into your home network, you can establish a robust security perimeter and gain granular control over network traffic. It acts as a gateway between your modem and the devices connected to your network, providing essential firewall protection, traffic filtering, VPN capabilities, and more. With pfSense, you can monitor and manage network traffic, implement access control policies, and secure your network against external threats.

Step-by-Step Installation on Mini PC Intel N5095:

Here's a step-by-step guide to installing pfSense on a Mini PC Intel N5095:

-  Prepare the Installation Media:
    -  Download the latest stable version of pfSense from the official website.
    -  Create a bootable USB drive using software like Rufus or Etcher.
-  Connect the Hardware:
    - Connect your Mini PC Intel N5095 to a monitor or TV using an HDMI cable.
    - Plug in a USB keyboard and a mouse.
    - Connect one of the LAN ports on the Mini PC to your modem using an Ethernet cable.
    - Boot from the Installation Media:
-  Insert the bootable USB drive into the Mini PC.
    -  Power on the Mini PC and enter the BIOS/UEFI settings by pressing the appropriate key (usually displayed during startup).
    -  Configure the BIOS to boot from the USB drive.
-  Install pfSense:
    -  The pfSense installation wizard will appear.
    -  Select the "Install" option to begin the installation process.
    -  Follow the on-screen prompts to choose the installation options, such as the installation destination and partitioning.
    -  Once the installation is complete, remove the USB drive and restart the Mini PC.
-  Initial Configuration:
    -  After rebooting, pfSense will load and present you with a series of configuration options.
    -  Configure the WAN interface by assigning it the appropriate IP address and gateway settings provided by your ISP.
    -  Set up the LAN interface by specifying the IP address range for your internal network (e.g., 192.168.1.0/24).
    -  Configure additional settings as required, such as DNS servers and time zone.
-  Access the pfSense Web Interface:
    -  Open a web browser on a device connected to your network.
    -  Enter the LAN IP address of the pfSense firewall in the address bar (e.g., http://192.168.1.1).
    -  You will be prompted to set a new password for the admin account.
    -  After setting the password, you will gain access to the pfSense web interface.
-  Customize pfSense:
    -  Explore the various features and configurations available in the web interface.
    -  Configure firewall rules, set up port forwarding, enable VPN services, and customize security settings based on your requirements.
    -  Connect the Mini PC's second LAN port to your wireless router to extend your network's connectivity.
By following these steps, you can install and configure pfSense on your Mini PC Intel N5095, allowing you to enhance the security and control of your home network.

# PfSense Web interface

![dash](https://github.com/HPastoral/PfSense-Firewall/assets/135756003/537f889c-7ea8-4d9c-ad42-2b2d8d559c43)

pfSense has a user-friendly graphical interface that allows you to configure and manage your pfSense firewall system. It provides a centralized platform for accessing and controlling various features, settings, and services of the firewall.

Here are some key aspects of the pfSense web interface:

Dashboard: The dashboard provides an overview of your system's status, including real-time information such as CPU and memory usage, network traffic graphs, system logs, and any active alerts or notifications. It offers a quick snapshot of your firewall's performance and current network conditions.

Menus and Navigation: The web interface is organized into various menus and submenus, offering easy navigation to different sections of configuration and management. Common menus include Interfaces, Firewall, Services, VPN, Diagnostics, and System. Each menu contains related settings and options, allowing you to customize and control specific aspects of your firewall.

Configuration: The web interface provides a comprehensive set of configuration options to fine-tune your firewall settings. You can define network interfaces, set up firewall rules to control traffic flow, configure NAT (Network Address Translation) rules, manage DHCP services, set up DNS servers, and more. These settings enable you to tailor the firewall behavior to suit your network requirements and security policies.

Monitoring and Logging: pfSense offers extensive monitoring and logging capabilities through its web interface. You can view real-time network traffic statistics, monitor bandwidth usage, track firewall events, and examine system logs for troubleshooting and security analysis. The interface provides visual graphs and tables to help you analyze network activity and identify any issues or anomalies.

Package Manager: pfSense supports various optional packages that can be installed and managed through the web interface. These packages enhance the functionality of your firewall by adding features such as intrusion detection and prevention (IDS/IPS), proxy servers, DNS filtering, caching, and more. The Package Manager allows you to easily install, update, and configure these additional components.

Security and Certificates: The web interface provides tools for managing security-related aspects of your firewall. You can generate and import SSL certificates for secure web access, set up VPN connections for remote access or site-to-site connectivity, configure firewall rules to protect your network, and enable security features like Secure Shell (SSH) access or Two-Factor Authentication (2FA).

System Administration: The web interface also includes administrative functions such as user management, system backups and restores, firmware upgrades, and general system configuration. You can create multiple user accounts with different access levels, ensuring that only authorized personnel can make changes to the firewall configuration.

Overall, the pfSense web interface simplifies the management and configuration of your firewall system, providing a user-friendly interface to control various aspects of network security, connectivity, and performance. It offers a powerful set of tools and features to customize your firewall according to your specific needs while maintaining a secure and robust network environment.
