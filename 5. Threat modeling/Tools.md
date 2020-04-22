# Threat Modeling Tools

[TOC]

## 1. MS Threat Modeling Tool

> For Learning:  https://docs.microsoft.com/zh-cn/azure/security/azure-security-threat-modeling-tool 
> For Templates: https://github.com/AzureArchitecture/threat-model-templates 
> For Download: https://aka.ms/threatmodelingtool 
>
> Main Site: https://www.microsoft.com/en-us/securityengineering/sdl/threatmodeling

The Threat Modeling Tool is a core element of the Microsoft Security Development Lifecycle (SDL). It allows software architects to identify and mitigate potential security issues early, when they are relatively easy and cost-effective to resolve. As a result, it greatly reduces the total cost of development. Also, we designed the tool with non-security experts in mind, making threat modeling easier for all developers by providing clear guidance on creating and analyzing threat models.

The tool enables anyone to:

- Communicate about the security design of their systems
- Analyze those designs for potential security issues using a proven methodology
- Suggest and manage mitigations for security issues

Here are some tooling capabilities and innovations, just to name a few:

- **Automation:** Guidance and feedback in drawing a model
- **STRIDE per Element:** Guided analysis of threats and mitigations
- **Reporting:** Security activities and testing in the verification phase
- **Unique Methodology:** Enables users to better visualize and understand threats
- **Designed for Developers and Centered on Software:** many approaches are centered on assets or attackers. We are centered on software. We build on activities that all software developers and architects are familiar with -- such as drawing pictures for their software architecture
- **Focused on Design Analysis:** The term "threat modeling" can refer to either a requirements or a design analysis technique. Sometimes, it refers to a complex blend of the two. The Microsoft SDL approach to threat modeling is a focused design analysis technique

###  How To:

The table below contains important links to get you started with the Threat Modeling Tool:

| Step  | Description                                                  |
| :---: | :----------------------------------------------------------- |
| **1** | [Download the Threat Modeling Tool](https://aka.ms/threatmodelingtool) |
| **2** | [Read Our getting started guide](https://docs.microsoft.com/en-us/azure/security/develop/threat-modeling-tool-getting-started) |
| **3** | [Get familiar with the features](https://docs.microsoft.com/en-us/azure/security/develop/threat-modeling-tool-feature-overview) |
| **4** | [Learn about generated threat categories](https://docs.microsoft.com/en-us/azure/security/develop/threat-modeling-tool-threats) |
| **5** | [Find mitigations to generated threats](https://docs.microsoft.com/en-us/azure/security/develop/threat-modeling-tool-mitigations) |

## 2. Other Tools

###  OWASP-threat-dragon

> http://docs.threatdragon.org/ 
>
> https://github.com/mike-goodwin/owasp-threat-dragon-desktop
>
> https://threatdragon.org/
>
> https://github.com/mike-goodwin/owasp-threat-dragon-desktop/releases

![image-20200422102425264](C:\Users\FenghuiXu\AppData\Roaming\Typora\typora-user-images\image-20200422102425264.png)

###  Octotrike

> https://www.octotrike.org/

Trike is an open source threat modeling methodology and tool. The project began in 2006 as an attempt to improve the efficiency and effectiveness of existing threat modeling methodologies, and is being actively used and developed. Trike is a platform-independent tool for systematic, computer-assisted threat modeling, from requirements through deployment.

"

We are developing Trike v2 on GitHub (https://github.com/octotrike/trike). Our mailing lists are still here on SourceForge, and we're leaving the old code repository & releases up for archival purposes. Plus you probably want to use something while you're waiting for v2.

###  SeaSponge

> https://github.com/mozilla/seasponge
>
> 

SeaSponge is an accessible web-based threat modeling tool developed for [Mozilla Winter of Security 2014](https://wiki.mozilla.org/Security/Automation/WinterOfSecurity2014).

This web-based application is being developed with three characteristics in mind:

- **Accessibility**: We want everyone to be able to map out their infrastructures and generate security reports on any operating-system and on any browser.
- **Aesthetics**: We're tired of clunky, boring interfaces - we want to bring the pizazz into threat-modeling.
- **Intuitive User-Experience**: We hate manuals, and we want you to be able to use this software without one.

![usage_demo](https://cloud.githubusercontent.com/assets/5893112/6827282/55cf9060-d2e5-11e4-802f-7663719ee873.gif)

