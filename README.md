# Lab 08 – Azure Monitor, Log Analytics, and Data Collection Rules (DCR)

## Overview
This lab demonstrates the implementation of centralized monitoring and telemetry collection for Azure virtual machines handling sensitive workloads. The configuration enables advanced visibility, threat detection, and integration with Microsoft security services.

---

## Objectives
- Deploy an Azure virtual machine (VM) with Encryption at Host enabled.
- Create a Log Analytics workspace to centralize logs and performance metrics.
- Set up an Azure Storage Account for monitoring and diagnostics.
- Configure a Data Collection Rule (DCR) to collect CPU, memory, disk, and network metrics from VMs.

---

## Key Skills Demonstrated
- Azure Virtual Machine deployment using Azure PowerShell
- Azure Monitor and Log Analytics workspace configuration
- Data Collection Rules (DCR) creation and integration with Azure Monitor
- Centralized telemetry collection for security and performance monitoring
- Security-aligned configurations, ready for Microsoft Defender for Cloud and Sentinel

---

## Screenshots
All exercises include screenshots to demonstrate each step of the lab:

- **Exercise 1:** Deploy Azure Virtual Machine  
- **Exercise 2:** Create Log Analytics Workspace  
- **Exercise 3:** Create Azure Storage Account  
- **Exercise 4:** Configure Data Collection Rule (DCR)  

Screenshots are located in the `screenshots/` folder within this repository.

---

## Result
Telemetry from the virtual machine is successfully collected and routed to the Log Analytics workspace. This setup provides centralized visibility across compute resources and integrates with Microsoft Defender for Cloud for enhanced security monitoring.

---

## Notes
- This lab is part of the Microsoft AZ-500 practical exercises.  
- While this repository contains only Lab 08, the configurations are fully functional and demonstrate core Azure monitoring and security skills.
