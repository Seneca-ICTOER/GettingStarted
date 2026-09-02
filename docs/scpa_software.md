---
id: software
title: Software
sidebar_position: 4
slug: /software
description: Student onboarding - SCPA software recommendations
---

# School of Computer Programming and Analysis \(SCPA\)

## Software

### Microsoft Office

Microsoft Office 365 Pro Plus is supplied by Seneca and used by everyone. It is strongly suggested you become familiar with the Microsoft Office 365 applications:

- Outlook (email)
- Word (word processing)
- Teams (collaboration)
- OneDrive (cloud storage)
- Excel (data analysis)
- PowerPoint (presentations)

:::tip FREE!
The Microsoft 365 suite of applications is free to install on your personal computer!
:::

#### Office Online Portal

- Online Office application can be accessed at [https://mySeneca.ca](https://mySeneca.ca) \(sign on using your SenecaID@mySeneca.ca account\ credentials)

#### Desktop Installation

- Full feature set of Office 365 applications is available for installation on your desktop \(only when installed on **your own computer at no charge**\)
- Sign on to [Office 365](http://www.office.com/) with your Seneca account
- From the "Install Office" drop-down menu near the top right, select Office 365 apps.

  :::warning
  If you have older or other versions of Microsoft Office apps already installed, it is strongly recommended that you uninstall them before installing Office 365.
  :::

### Development Tools

#### Windows (Visual Studio Community)

The Visual Studio Community version IDE \(Integrated Development Environment\) is a professional-grade development tool widely used by industry leaders. [Visual Studio - Community Edition](https://visualstudio.microsoft.com/free-developer-offers/) is free!

:::note Studio vs Code
Do not confuse Visual **Studio** with Visual Studio **Code**! Visual Studio **Code** does not install a C/C++ compiler and requires many extra steps to configure for C/C++ development. You should install **Visual Studio Community**!
:::

- **Visual Studio Community**:

  - Download VS Community installer application: [Direct Download](https://visualstudio.microsoft.com/thank-you-downloading-visual-studio/?sku=Community&channel=Stable&version=VS18&source=VSLandingPage&cid=2500&passive=false)

  - Execute the downloaded installer application \(**NOTE**: use the defaults unless you know exactly what you are doing\)
  - When prompted for the \"**Workloads**\", you only need to select **`Desktop development with C++`**. This option is located in the section **\"Desktop and Mobile\"**:

    <img width="350" src="./img/vscworkflow.png"/>

    After selecting the C/C++ workflow, on the **RIGHT-SIDE** panel in the section **\"Desktop development with C++\"**, **UNCHECK/DE-SELECT** the two options for Copilot integration \(_you can always add this back AFTER you learn the foundations of programming_\):

    <img width="350" src="./img/vscworkflow-nocopilot.png"/>

    **NOTE**: If you missed these steps, you can always run the installer again, only this time **modify** your installation and add the workflow accordingly.

  - Click the **`Install`** button located at the bottom-right corner to complete the installation

- **Visual Code** (_Optional_):

  This section is for those who are more comfortable or interested in using **Visual Studio Code** to develop in as their primary IDE \(should only be considered if you have already installed **Visual Studio Community**\).

  - Refer to Microsoft's documentation for VS Code installation and configuration for C/C++ development [VS Code for C/C++ \(https://code.visualstudio.com/docs/cpp/config-msvc\)](https://code.visualstudio.com/docs/cpp/config-msvc)

#### Mac OSX (xCode)

The C/C++ development tools in Visual **Studio** is not available for Mac OS. Students who wish to use Mac OS to do their work can alternatively use the following tools \(_Thanks to Dr. P. Denny of The University of Aukland!_\):

- **xCode**: [Follow these instructions to use xCode](https://www.cs.auckland.ac.nz/~paul/C/Mac/xcode/)
  - This will install the C/C++ compiler, IDE, Git Tools, and the command line tools
- **Visual Studio Code**: After installing xCode, you can optionally use the VS Code IDE for your code development ([Follow these instructions to use Visual Studio Code](https://www.cs.auckland.ac.nz/~paul/C/Mac/))

### Git Tools

#### Windows

Git Tools Download: https://git-scm.com/install/windows

- Select the **\"Git for Windows/x64 Setup\"** link
- Execute the downloaded installer and apply the defaults
- It is a good idea to logout of your machine and back in after installation \(there are environment variables that need to be active to use the git tools effectively\).

#### Mac OSX

It is not necessary to explicitly install the Git Tools if you installed xCode \(above\). It is strongly advised you install xCode which comes packaged with the Git Tools as part of that installation. However, if you do not have xCode, you can still install the Git tools:

- https://git-scm.com/install/mac
- Follow the installation instructions

### VPN ([Virtual Private Network](https://en.wikipedia.org/wiki/Virtual_private_network))

When you are off-campus and wish to access Seneca's servers/services, you will need to use a specific VPN client. Please reference the following document for instructions:

- [GlobalProtect VPN](https://students.senecapolytechnic.ca/spaces/186/it-services/wiki/view/1024/vpn) - See the Students section and install on your system.

:::note On-Campus
When you are on-campus using a lab computer or your device is connected using Seneca's secured SenecaNet WIFI \(not the GUEST option\), the VPN is NOT required. In fact, when you connect to the VPN on-site, it will not work. Only use the VPN when you are off-site.
:::

## Popular Seneca Web Portals

- [https://my.senecapolytechnic.ca](https://my.senecapolytechnic.ca) where your courses reside inside the Blackboard Learning Management System
- [https://myseneca.ca](https://myseneca.ca) to access your Microsoft Outlook email in your browser
- [SCPA](https://www.senecapolytechnic.ca/school/computer-programming-and-analysis.html) CPP and CPA Program details
