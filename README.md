# AVT - Automation Vulnerability Tool (Final Prototype)

[![Go Version](https://img.shields.io/badge/Go-1.21+-00ADD8?style=flat&logo=go)](https://go.dev/)
[![Nmap](https://img.shields.io/badge/Tools-Nmap-blue)](https://nmap.org/)
[![Nuclei](https://img.shields.io/badge/Tools-Nuclei-yellow)](https://nuclei.projectdiscovery.io/)
[![Wails](https://img.shields.io/badge/Wails-v2-red?style=flat&logo=wails)](https://wails.io/)
[![Svelte](https://img.shields.io/badge/Svelte-4.0-ff3e00?style=flat&logo=svelte)](https://svelte.dev/)
![License](https://img.shields.io/badge/license-All%20Rights%20Reserved-red)

# Description
AVT is a desktop-based application designed to integrate two renowned security assessment tools **Nmap** and **Nuclei**.

This project aims to streamline the network-based IT infrastructure audit process by adopting the **NIST SP 800-115 framework**. The system guides users through structured security assessment stages, ranging from asset mapping to vulnerability scanning.

# Features
The features within this system include:
- **Assessment from the NIST SP 800-115 stages:**
  - `Planning`
  - `Discovery`
  - `Attack`
  - `Reporting`
  - `(Additional Discovery)`
- Clear documentation at each stage
- Custom scripts (Including Nmap and Nuclei)
- Reporting history
- Data that can be linked to a vulnerability database
- A vulnerability database that can be configured according to user preferences

# Prerequisites
Since this project utilizes Nmap and Nuclei, both tools must be installed before proceeding. Below are the links where you can download them (if you do not have them installed yet) :
| Component | Desc | Link |
| :--- | :--- | :--- |
| **Nmap** | Network Mapping & Port Scanner | [Official Download](https://nmap.org/download.html) |
| **Nuclei** | Vulnerability Scanning Engine | [GitHub Repository](https://github.com/projectdiscovery/nuclei) |
| **Nuclei Templates** | Community-curated Vulnerability Ruleset | [Github Repository](https://github.com/projectdiscovery/nuclei-templates) |
| **Vulnerability Database** | Centralized Github advisories database | [Clock](https://rushdie.vercel.app/thing-features) |

# Documentation
The complete documentation for the system is provided below. Please choose only one option : 

[![Markdown](https://img.shields.io/badge/Documentation-Markdown-000000?style=for-the-badge&logo=markdown&logoColor=white)](https://rushdie.vercel.app/docs/manual.md) &nbsp;&nbsp;&nbsp; [![PDF](https://img.shields.io/badge/Documentation-PDF-EC1C24?style=for-the-badge&logo=protondrive&logoColor=white)](https://rushdie.vercel.app/docs/manual.pdf)

# License
Copyright © 2026 Bhara Satriyanto. All rights reserved.

All source code and system architecture within this AVT project are private. Unauthorized use, copying, or redistribution without written permission from the copyright owner is strictly prohibited. Thank you for your understanding and respect.
