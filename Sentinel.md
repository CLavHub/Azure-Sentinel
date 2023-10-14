Azure Sentinel is a cloud-native, scalable Security Information and Event Management (SIEM) service provided by Microsoft Azure. It allows organizations to collect, analyze, and act on security data from various sources, helping to detect and respond to security threats and incidents. This lab also works in tangent with Virtual Machines, Log Analytics Workspace and Microsoft Defender. 

I followed a lab created by Josh Makador, here is the [video](https://youtu.be/RoZeVbbZ0o0?si=S-Y-lnG0aiwvNuZf)

The lab begins by needing an Azure account. Creating an account gave me $200 which can suffice for the tools this lab needs. The main hub of this lab is going to be [Azure Portal](https://azure.microsoft.com/en-us/get-started/azure-portal). The first step is to create a Virtual Machine that is stripped of it's security measures. The Virtual Machine will act as a honeypot to attract various hackers, bots, etc. They will attempt to gain entry to the VM with RDP. 

