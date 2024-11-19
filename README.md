# Global Services Customer Requirments
Welcome to the Customer Requirments portal for Global Services deployments.  This site provies common customer requirments that need to be completed prior to kicking off the deployment of specific configuration items.  Details about which configuration items are applicible to your deployment, please consult with your project team.

<details markdown="1">
<summary markdown="1">
Core Platform Configuration Items
</summary>
The following configuration items relate to the installation and configuration of the core platform components.  These configuration items should be reviewed and understood prior to completion of addtional configuration items.
<hr>
<br/>

|Configuration Item |Description |Customer Requirments |Tags|
|:------------------|:------------------|:------------------|:----------|
|Platform Install |The core Keyfactor Command Platform is to be hosted by the customer on their own infrastructure.   | [Server Requirments](https://software.keyfactor.com/Core-OnPrem/current/Content/InstallingServer/Main/System%20Requirements.htm){:target="_blank" rel="noopener"}<br/><br/>[Addtional Customer Responsibilities](https://software.keyfactor.com/Core-OnPrem/current/Content/InstallingServer/Main/Planning%20for%20Keyfactor.htm){:target="_blank" rel="noopener"}|
|Universal Orchestrator Base Install|The Universal Orchestrator Service is installed locally and communicates to Command to execute SSL Discovery & Certificate Store jobs|[Server Requirements](https://software.keyfactor.com/Core-OnPrem/current/Content/InstallingAgents/NetCoreOrchestrator/SystemRequirements.htm){:target="_blank" rel="noopener"}<br/><br/>[Addtional Customer Responsibilities](https://software.keyfactor.com/Core-OnPrem/current/Content/InstallingAgents/NetCoreOrchestrator/Preparing.htm){:target="_blank" rel="noopener"}|
|AnyCA Gateway Install|The AnyCA Gateway enables synchronization and enrollment access to public and third party CAs.|[Server Requirements](https://software.keyfactor.com/Guides/AnyGateway_Generic/Content/AnyGateway/SystemRequirements.htm){:target="_blank" rel="noopener"}<br/><br/>[Addtional Customer Responsibilities](https://software.keyfactor.com/Guides/AnyGateway_Generic/Content/AnyGateway/Preparing.htm){:target="_blank" rel="noopener"}|
</details>

{::options parse_block_html="false" /}

<br/>
<br/>

{::options parse_block_html="true" /}

<details markdown="1">
<summary markdown="1">
AnyCA Gateway Plug-ins
</summary>
This section relates to exension of the AnyCA Gateway with specific integration components.  These components are installed and configured within the base install referenced above.  For more information about the AnyCA Gateway, visit the product documentation.

[AnyCA Gateway REST](https://software.keyfactor.com/Guides/AnyCAGatewayREST/Content/AnyCAGatewayREST/Introduction.htm){:target="_blank" rel="noopener"} 

[AnyCA Gateway DCOM](https://software.keyfactor.com/Guides/AnyGateway_Generic/Content/AnyGateway/Introduction.htm){:target="_blank" rel="noopener"}
<hr/>
<br/>

|Configuration Item |Description |Customer Requirments |Tags|
|:------------------|:------------------|:------------------|:----------|
|**AnyCA Gateway Plug-in:** Digicert Cert Central|This AnyCA Gateway Plug-in enables access to Digicert's Cert Central platform.|[Extension Requirements](https://github.com/Keyfactor/digicert-certcentral-caplugin?tab=readme-ov-file#prerequisites){:target="_blank" rel="noopener"}|
|**AnyCA Gateway Plug-in:** Sectigo Certificate Manager|This AnyCA Gateway Plug-in enables access to Sectigo's Certificate Manager Platform|[Extenstion Requirments](https://github.com/Keyfactor/sectigo-certmanager-cagateway?tab=readme-ov-file#prerequisites){:target="_blank" rel="noopener"}|
</details>

{::options parse_block_html="false" /}

<br/>
<br/>

{::options parse_block_html="true" /}

<details markdown="1">
<summary markdown="1">
Universal Orchestrator Extensions
</summary>
This section relates to the installation and configuration of various orchestrator extensions that provide addtional capabilies to the orchestrator framework.  For more inforamtion about the Universal Orchestrator, visit the product documenation

[Universal Orchestrator](https://software.keyfactor.com/Core-OnPrem/current/Content/InstallingAgents/Introduction.htm){:target="_blank" rel="noopener"}
<hr/>
<br/>

|Configuration Item |Description |Customer Requirments |Tags|
|:------------------|:------------------|:------------------|:----------|
|**Orchestrator Extension:** Azure Application Gateway|This extension enables the creation and management of certificate stores linked to the Azure Application Gateway.  This extension supports both certificates and certificates with bindings| [Extension Requirments](https://github.com/Keyfactor/azure-appgateway-orchestrator?tab=readme-ov-file#installation){:target="_blank" rel="noopener"}|
|**Orchestrator Extension:** Remote File Orchestrator|This extension supports numerous file based certificate store types including JKS, PEM, DER, and PKCS12.| [Extension Requirments](https://github.com/Keyfactor/remote-file-orchestrator?tab=readme-ov-file#requirements--prerequisites){:target="_blank" rel="noopener"}|
|**Orchestrator Extension:** IIS Orchestrator|This extension supports the inventory and management of the Windows Local Machine Certificate Stores (e.g. Personal, Trusted Roots, and Web Hosting)|[Extension Requirments](https://github.com/Keyfactor/iis-orchestrator?tab=readme-ov-file#wincertstore-orchestrator-configuration){:target="_blank" rel="noopener"}|
</details>

{::options parse_block_html="false" /}


