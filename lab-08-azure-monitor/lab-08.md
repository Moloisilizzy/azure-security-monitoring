## Exercise 1: Deploy an Azure Virtual Machine

A Windows virtual machine was deployed using Azure PowerShell to serve as the telemetry source for monitoring and security services. Encryption at Host was enabled to align with data protection best practices.

### Screenshots

![Resource group created](screenshots/exercise-01-vm-deployment/lab801.png)

![VM deployment command](screenshots/exercise-01-vm-deployment/Screenshot2.png)

![Provisioning succeeded](screenshots/exercise-01-vm-deployment/Screenshot3.png)

![VM overview](screenshots/exercise-01-vm-deployment/Screenshot4.png)

---

## Exercise 2: Create a Log Analytics Workspace

A Log Analytics Workspace was created to centralize performance metrics and system logs collected from Azure virtual machines. This workspace is required for Microsoft Defender for Cloud and Microsoft Sentinel.

### Screenshots

![Log Analytics workspace configuration](screenshots/exercise-02-log-analytics/lab802.png)

![Log Analytics workspace created](screenshots/exercise-02-log-analytics/Screenshot6.png)

---

## Exercise 3: Create an Azure Storage Account

An Azure Storage Account was deployed to support Azure monitoring and diagnostic services.

### Screenshots

![Storage account created](screenshots/exercise-03-storage-account/lab803.png)

---

## Exercise 4: Create a Data Collection Rule (DCR)

A Data Collection Rule was configured using Azure Monitor Agent to collect performance counters from Windows virtual machines and route the data to Log Analytics.

Collected metrics include CPU, memory, disk, and network performance at 60-second intervals.

### Screenshots

![DCR performance counters](screenshots/exercise-04-dcr/lab804.png)

![DCR destination Log Analytics](screenshots/exercise-04-dcr/Screenshot9.png)