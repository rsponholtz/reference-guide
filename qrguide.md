
# Quick reference Guide for SAP on Microsoft for Customers and Partners

| Architecture Reference                    | Infrastructure  |
| ----------------------------------------- | ------------------------------|
| [SAP on Azure reference architecture](https://docs.microsoft.com/en-us/azure/architecture/reference-architectures/sap/sap-overview) | [Azure Paired Regions]()
|[Enterprise Scale for SAP](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/scenarios/sap/enterprise-scale-landing-zone)| [ANF Paired regions for CRR]()
||[Use ExpressRoute for on-prem to Azure Connectivity]()
||[Consider GlobalReach](https://docs.microsoft.com/en-us/azure/virtual-machines/workloads/sap/hana-connect-vnet-express-route)
|| [Consider FastPath to improve network performance for HLIs](https://docs.microsoft.com/en-us/azure/virtual-machines/workloads/sap/hana-connect-vnet-express-route)
|| [Check Operating systems supported for HANA]()
|| [Check SAP Certified Azure VMs and Bare Metal instances](https://www.sap.com/dmc/exp/2014-09-02-hana-hardware/enEN/#/solutions?filters=v:deCertified;ve:24)
|| [Consider Accelerated Networking for E/M series]()
|| For ANF, [consider PPG pinning](https://forms.office.com/Pages/ResponsePage.aspx?id=v4j5cvGGr0GRqy180BHbRxjSlHBUxkJBjmARn57skvdUQlJaV0ZBOE1PUkhOVk40WjZZQVJXRzI2RC4u) refer for best practices
|| For ANF, [Consider AzAcSnap for snapshots](https://docs.microsoft.com/en-us/azure/azure-netapp-files/azacsnap-introduction) for Oracle and HANA
|| For Azure premium storage  **/hana/log** is required to be supported by Azure [Write Accelerator](https://docs.microsoft.com/en-us/azure/virtual-machines/how-to-enable-write-accelerator)
|| Use ASR for Application layer replication
|| use Azure Backup for VM, SQL and HANA DBs 
|| [Consider SSO and authentication using AD](https://docs.microsoft.com/en-us/azure/active-directory/saas-apps/sap-netweaver-tutorial)
|| [Azure Policy and RBAC]()
|| [Consider Monitor SAP on Azure](https://docs.microsoft.com/en-us/azure/virtual-machines/workloads/sap/monitor-sap-on-azure) 
|| [Azure Sentinel for SAP threat detection](https://docs.microsoft.com/en-Us/azure/sentinel/sap-deploy-solution)
|| [Consider combining SAP S/4HANA conversion with the move to Azure](https://blogs.sap.com/2021/12/02/dmo-to-azure-combine-sap-s-4hana-conversion-with-the-move-to-azure-without-dmo-with-system-move/)

| Operations and support                   | Others useful tools/Links  |
| ----------------------------------------- | ------------------------------|
| [SAP Applications on Azure: Supported Products and Sizing](https://launchpad.support.sap.com/#/notes/1928533) | [Costing -- Azure calculator](https://azure.microsoft.com/en-us/pricing/calculator/) |
| [Azure SLA](https://azure.microsoft.com/en-us/support/legal/sla/) | [Check VM availability in zones](https://github.com/Azure/SAP-on-Azure-Scripts-and-Utilities/tree/main/Get-VM-by-Zones)  |
| [Azure Support Plans](https://azure.microsoft.com/en-us/support/options/#support-plans) | [Custom dashboard for cost optimization](https://github.com/Azure/SAP-on-Azure-Scripts-and-Utilities/tree/main/Costmanagement-Dashboard) |
| [Create an Azure support request](https://docs.microsoft.com/en-us/azure/azure-portal/supportability/how-to-create-azure-support-request) | [SAP HANA Automated deployment](https://github.com/Azure/sap-automation) |
| | [Az zone Latency test](https://github.com/Azure/SAP-on-Azure-Scripts-and-Utilities/tree/main/AvZone-Latency-Test) |
| | [Start/Stop Azure SAP VM](https://github.com/Azure/SAP-on-Azure-Scripts-and-Utilities/tree/main/Start-Stop-Automation) |
| | [Quality check of the system](https://github.com/Azure/SAP-on-Azure-Scripts-and-Utilities/tree/main/QualityCheck) |
| | [SAP on Azure WAF](https://docs.microsoft.com/en-us/assessments/?mode=pre-assessment&session=local) |
| | [Grow/manage ANF volumes](https://github.com/ANFTechTeam/ANFCapacityManager) |
| | [ANF Health Check](https://github.com/seanluce/ANFHealthCheck) |
| | [Azure Resource Group Copy](https://github.com/Azure/RGCOPY) |
| | Azure Inventory Checks for SAP (Upcoming) |
| | Azure Deployment Checklist (Upcoming)
| | Azure VM OS Analyzer for SAP (Upcoming)

| Must Read                   | OSS Notes    |
| ----------------------------------------- | ------------------------------|
| [Use Azure to host and run SAP workload scenarios](https://docs.microsoft.com/en-us/azure/virtual-machines/workloads/sap/get-started) | [Certified and Supported SAP HANA® Hardware](https://www.sap.com/dmc/exp/2014-09-02-hana-hardware/enEN/#/solutions?filters=v:deCertified;ve:24)|                                
| [Running SAP Applications on the Microsoft Platform - Microsoft Tech Community](https://techcommunity.microsoft.com/t5/running-sap-applications-on-the/bg-p/SAPApplications) | [2015553 - SAP on Microsoft Azure: Support prerequisites](https://launchpad.support.sap.com/#/notes/2015553)
||[1928533 - SAP Applications on Microsoft Azure: Supported Products and Azure VM types](https://launchpad.support.sap.com/#/notes/1928533)
| [Learn SAP on Azure for AZ-120 Certification](https://docs.microsoft.com/en-us/learn/browse/?terms=sap) |

| Interface/Connectivity                   |
| ----------------------------------------- |
| [ADF Table Connector](https://docs.microsoft.com/en-us/azure/data-factory/connector-sap-table?tabs=data-factory)| 
| [ADF ECC Connector](https://docs.microsoft.com/en-us/azure/data-factory/connector-sap-ecc?tabs=data-factory)|
| [ADF HANA Connector](https://docs.microsoft.com/en-us/azure/data-factory/connector-sap-hana?tabs=data-factory)|
| [Power Platform and SAP](https://docs.microsoft.com/en-us/power-platform-release-plan/2021wave1/data-integration/sap-erp-connector-power-automate-power-apps) |
| [SSO](https://docs.microsoft.com/en-us/azure/active-directory/saas-apps/sap-netweaver-tutorial) |
| [Logic Apps and SAP](https://docs.microsoft.com/en-us/azure/logic-apps/logic-apps-using-sap-connector) |

| Glossary |
| ----------------------------------------- |
| ADF - Azure Data Factory
| ANF - Azure Netapp Files
| ASR - Azure Site Recovery
| CRR - Cross Region Replication
| PPG - Proximity Placement Group
| SSO - Single Sign On
| WAF - Well Architected Framework 
