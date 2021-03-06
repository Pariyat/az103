# Microsoft Course AZ-103

*Field notes by Erik Caha*

## Setup Environment

You need trial account, azure pass or other access to Microsoft Azure. The best practice is to use separate purpose build account for this task. For example, create new gmail account, then create new Microsoft account for this new email, redeem code for new account (or use credit card for trial account verification). Credit card for trial account cannot be connected to Azure ever before. Electronic credit card can be used. For trial account, the card is used only for verification and is never charged.

Install Azure CLI. Azure CLI is preferred command line tool to work with Azure. It is multiplatform tool (you can run Azure CLI on MacOS, Linux, Windows and if you try little bit harder even on BSD like UNIX).

For convenient PowerShell experience install latest version of PowerShell and install Az module. There was big change in Azure modules on the beginning of the year 2019. You can still find two different command sets (AzureRmSomething, AzSomething). Try to use Az version whenever it is possible, it is newer with bright future. Even reworking older syntax (AzureRm) to new one will pay off in the future.

## External links

* [Tagging template](https://slstudentpublic.blob.core.windows.net/governance/Tagging.xlsx)
* [Naming template](https://slstudentpublic.blob.core.windows.net/governance/NamingStandards.xlsx)

* [AZ-103 github HOL](https://github.com/MicrosoftLearning/AZ-103-MicrosoftAzureAdministrator/tree/master/Instructions/Labs) [All files direct download](https://github.com/MicrosoftLearning/AZ-103-MicrosoftAzureAdministrator/archive/master.zip)
* [Kubernetes HOL](https://github.com/MicrosoftLearning/AZ-203-DevelopingSolutionsforMicrosoftAzure/blob/master/Instructions/Labs/AZ-203_02_lab.md)

## Modules

### Virtual machine

### Storage Account
[All demonostrations here](StorageAccount.md)

### Networking
Optional advanced labs for the Network Virtula Appliance (Linux based). [Link](https://github.com/erjosito/azure-networking-lab)
