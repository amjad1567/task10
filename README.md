Here’s a sample **README.md** file for your report and repository:

---

# Network and Router Configuration Report

## Introduction
This repository contains a detailed report on the network configuration and router details for a specific ISP and device setup. The purpose of this project is to document key network and router information, including **ISP details**, **device details**, **WiFi password**, **network configuration**, and **connected devices**. Screenshots of relevant configurations and steps are included for reference.

## Repository Contents
- **Report.pdf**: A comprehensive report detailing the findings of the network and router setup.
- **ISP_Details.md**: Information about the ISP provider, ASN, and other ISP-related details.
- **Device_Details.md**: Specifications and connection type for the router device.
- **WiFi_Password_Details.md**: Documentation of the default and updated WiFi passwords.
- **Network_Configuration.md**: Steps and configurations taken for the network setup, including IP address, subnet mask, and DHCP settings.
- **Router_Login_Details.md**: Information regarding the router login, changes made, and access to the router dashboard.
- **Connected_Devices.md**: A list of devices connected to the router with relevant screenshots.
- **Screenshots**: A folder containing all the referenced screenshots (Figures 1-9) for each step mentioned in the report.

## Prerequisites
- Basic knowledge of network configurations and router settings.
- Access to a router’s login page and control panel.

## Repository Structure
```
/root
│
├── Report.pdf
├── ISP_Details.md
├── Device_Details.md
├── WiFi_Password_Details.md
├── Network_Configuration.md
├── Router_Login_Details.md
├── Connected_Devices.md
└── /Screenshots
    ├── Fig_1.png
    ├── Fig_2.png
    ├── Fig_3.png
    ├── Fig_4.png
    ├── Fig_5.png
    ├── Fig_6.png
    ├── Fig_7.png
    ├── Fig_8.png
    └── Fig_9.png
```

## Key Findings

### 1. ISP Details
- **ISP Provider**: Reliance Jio Infocomm Limited
- **ASN**: AS55836 RELIANCEJIO-IN (Registered Oct 27, 2010)
- Relevant Figures: [Fig 1](./Screenshots/Fig_1.png) & [Fig 2](./Screenshots/Fig_2.png)

### 2. Device Details
- **Device Model**: JCOW411
- **Connection Type**: Optical fiber connection
- Relevant Figures: [Fig 3](./Screenshots/Fig_3.png) & [Fig 4](./Screenshots/Fig_4.png)

### 3. WiFi Password Details
- **Default Password**: Jiocentrum
- Changed to a secure password after successful login.
  
### 4. Network Configuration
- Gathered data via **Control Panel -> Network and Internet -> Network Connections** and the **Command Prompt** using `ipconfig /all`.
- **Router IP Address**: 192.168.29.236
- **Subnet Mask**: 255.255.255.0
- **DHCP Start IP**: 192.168.29.1
- **DHCP End IP**: 192.168.29.256
- **DNS Mode**: From ISP
- Relevant Figures: [Fig 5](./Screenshots/Fig_5.png) & [Fig 6](./Screenshots/Fig_6.png)

### 5. Router Login Details
- Successful login using default password `Jiocentrum`.
- Password changed and the router was relogged.
- Access to the router dashboard was achieved.
- Relevant Figures: [Fig 7](./Screenshots/Fig_7.png) & [Fig 8](./Screenshots/Fig_8.png)

### 6. Connected Devices
- All connected devices were identified and documented.
- Relevant Figure: [Fig 9](./Screenshots/Fig_9.png)

## Conclusion
This report highlights essential network configuration steps, router details, and security improvements (such as changing default passwords) in a Reliance Jio Infocomm Limited network setup. By gathering relevant network data, this report provides insights into maintaining a secure home network.
