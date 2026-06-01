# AVT - Automation Vulnerability Tool

[![Go Version](https://img.shields.io/badge/Go-1.21+-00ADD8?style=flat&logo=go)](https://go.dev/)
[![Nmap](https://img.shields.io/badge/Tools-Nmap-blue)](https://nmap.org/)
[![Nuclei](https://img.shields.io/badge/Tools-Nuclei-yellow)](https://nuclei.projectdiscovery.io/)
[![Wails](https://img.shields.io/badge/Wails-v2-red?style=flat&logo=wails)](https://wails.io/)
[![Svelte](https://img.shields.io/badge/Svelte-4.0-ff3e00?style=flat&logo=svelte)](https://svelte.dev/)
![License](https://img.shields.io/badge/license-All%20Rights%20Reserved-red)

## Description
AVT is a desktop-based application designed to integrate two renowned security assessment tools **Nmap** and **Nuclei**.

This project aims to streamline the network-based IT infrastructure audit process by adopting the **NIST SP 800-115 framework**. The system guides users through structured security assessment stages, ranging from asset mapping to vulnerability scanning.

## Features
* **NIST SP 800-115 Compliant Assessment:**
  * **Planning:** Initial scope definition and rule engagement setup.
  * **Discovery:** Asset identification and network mapping (includes *Additional Discovery* capabilities).
  * **Attack:** Vulnerability validation and target exploitation simulation.
  * **Reporting:** Generation of structured executive summaries and technical findings.
* **Comprehensive Documentation:** Clear, step-by-step documentation logged at every assessment stage.
* **Custom Scripting Support:** Seamless integration and execution of custom scripts, including **Nmap** and **Nuclei**.
* **Report History Management:** A dedicated tracking system to store, view, and manage past assessment reports.
* **Vulnerability Database Integration:** Ability to cross-reference and link scan data with external vulnerability advisory databases.
* **Customisable Vulnerability Database:** A user-managed vulnerability database that can be tailored and updated according to specific requirements.
