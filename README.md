# **grc4ciso (GRC + XDR + GPT + ZT)**

### **Introduction**

grc4ciso integrates GRC, XDR, Zero Trust and GPT cybersecurity capabilities into a unified Software-as-a-Service (SaaS) platform.

This platform provides you:

- Governance, Risk, and Compliance (**GRC**): this is a community module hosted by OWASP projects https://github.com/OWASP/www-project-it-grc 
- Extended Detection and Response (**XDR**): endpoint security, configuration assessment, malware detection, file integrity monitoring, threat Intelligence, log data analysis, vulnerability detection, security operations, incident response, regulatory compliance, cloud security, container security.
- **GPT** assistant: GPT virtual CISO assistant integrated into the GRC module to provide you advise about cybersecurity activities, the GPT-4 assistant is also integrated into the XDR module to provide you information about the endpoints connected and alerts.
- **Zero Trust**: provide you the required components to implement a zero trust overlay network to protect web applications and services.

**With this platform you can get the power of these cybersecurity tools into a single SaaS platform!!**

<img width="959" alt="grc4ciso_1" src="https://github.com/grcbit/grc4ciso/assets/60721087/b9ece702-c369-40e5-98b2-4199330e3b58">

## **GRC (Governance, Risk and Compliance)**

Visit https://github.com/OWASP/www-project-it-grc to know the basic features of GRC module.

## **XDR**

XDR functionalities are based on wazuh platform, Wazuh is a free and open source platform used for threat prevention, detection, and response. It is capable of protecting workloads across on-premises, virtualized, containerized, and cloud-based environments.

Wazuh solution consists of an endpoint security agent, deployed to the monitored systems, and a management server, which collects and analyzes data gathered by the agents. Besides, Wazuh has been fully integrated with the Elastic Stack, providing a search engine and data visualization tool that allows users to navigate through their security alerts.

**With grc4ciso you can increase the power of this tool, because you can analize the data generated by the XDR with GPT-4, and you can register the incidents identified, define containment and recovery actions from an attack.**
**Having all these functionalities in the same platform give you more capabilities to protect your IT systems combining GRC + GPT + XDR + Zero Trust capabilities.**

<img width="959" alt="image" src="https://github.com/grcbit/grc4ciso/assets/60721087/13252dea-d3c5-4fba-9022-98c154b9b7ec">


## **GPT**

**grc4ciso** integrates a **GPT assistant** that is trained to advised you on Cybersecurity activities, so you have a virtual CISO helping you to manage cybersecurity activities all time you need it.

<img width="959" alt="image" src="https://github.com/grcbit/grc4ciso/assets/60721087/e04d77a0-50f9-4910-b63b-1c7ff90ed363">

This assistant can provide you information about your GRC profile (strategic risks, risk factors, controls, complicance, IT assets, threat scenarios).

Also if you are using the **XDR** module, the assistant can give you information about the endpoints that are connected to your **XDR**, so, you can for example ask the **grc4ciso GPT assistant** to summarize the main vulnerabilities you have in your systems, so you can take needed actions to mitigate cybersecurity risks.

<a name="prompts"></a>
### **Prompts Examples**

| Prompt Example | Description | Required parameter | Module | Language |
|----------------|-------------|--------------------|--------|----------|
| Return information about the XDR agents | Return information about all available agents or a list of them (ID, IP, name, status, operating system) |  | XDR | en |
| Return the active configuration about the XDR agent 001 | Return the active configuration the agent is currently using | agent ID | XDR | en |
| Return the TCP ports info for the XDR agent 001 | Return the agent's ports info | agent ID | XDR | en |
| Return the processes info for the XDR agent 001 | Return the agent's processes info | agent ID | XDR | en |
| Return the package info for the XDR agent 001 | Return the agent's packages info. This information include name, section, size, priority information of all packages among others | agent ID | XDR | en |
| Return the 001 XDR agent Operating System info | Return the agent's OS info. This information include os information, architecture information among others of all agents | agent ID | XDR | en |
| Return the 001 XDR agent routing configuration | Return the agent's routing configuration for each network interface | agent ID | XDR | en |
| Return the 001 XDR agent network address info | Return the agent's network address info. This information include used IP protocol, interface, IP address among others | agent ID | XDR | en |
| Return all hotfixes installed by Microsoft in the 001 XDR agent | Return all hotfixes installed by Microsoft(R) in Windows(R) systems (KB... fixes) | agent ID | XDR | en |
| Return the 001 XDR agent hardware info | Return the agent's hardware info. This information include cpu, ram, scan info among others | agent ID | XDR | en |
| Return the security SCA database of the 001 XDR agent | Return the security SCA database of an agent | agent ID | XDR | en |
| Return the last syscheck scan of the 001 XDR agent | Return when the last File integrity monitoring scan started and ended. It checks configured files for changes to the checksums, permissions and ownership | agent ID | XDR | en |
| Run File integrity monitoring scan in all agents | Run File integrity monitoring scan in all agents | agent ID | XDR | en |
| Return the File integrity monitoring findings in the 001 XDR agent | Return File integrity monitoring findings in the specified agent | agent ID | XDR | en |
| Return XDR statistical information | Return XDR statistical information for the current or specified date (total alerts and events) | | XDR | en |
| Return a summary of the XDR log entries | Return a summary of the last 2000 XDR log entries | | XDR | en |
| Return the data asset summary of the GRC module | Return the data asset summary of the GRC module. This information include description, data classification, owner, security requirement info among others | | GRC | en |
| Return the data classification summary of the GRC module | Return the data classification summary of the GRC module. This information include name and description | | GRC | en |
| Return the supplier summary of the GRC module | Return the supplier summary of the GRC module. This information include name and description | | GRC | en |
| Return the business process summary of the GRC module | Return the business process summary of the GRC module. This information include name, owner and description | | GRC | en |
| 1) Return the ISO27001:2022 statement of applicability summary of the GRC module. 2) Return the ISO27001:2022 requirement 5.11 statement of applicability summary of the GRC module | Return the ISO27001:2022 statement of applicability summary of the GRC module. This information include ISO requirement, aplicability, reason, status | | GRC | en |
|Return the Information Security Management System Roles summary of the GRC module | Return the Information Security Management System Roles summary of the GRC module. This information include role name, responsibilities | | GRC | en |
||||||

Our ChatGPT for Cybersecurity module is a state-of-the-art virtual assistant tailored for cybersecurity teams and small to medium-sized businesses (SMBs). It acts as a virtual Chief Information Security Officer (CISO) or governance advisor, ready to answer questions about governance, risk, compliance (GRC), threat detection, and more. This AI-driven assistant is designed to help organizations stay compliant, mitigate risks, and navigate the complexities of cybersecurity without needing in-depth technical knowledge.

## **ZeroTrust**

grc4ciso provides you all the needed components to create a Zero Trust network to protect you web applications and services, it is based on the openziti platform. OpenZiti is a free and open source project focused on bringing zero trust networking principles directly into any application. The project provides all the pieces required to implement a zero trust overlay network and provides all the tools necessary to integrate zero trust into your existing solutions. 

<img width="959" alt="image" src="https://github.com/grcbit/grc4ciso/assets/60721087/5203d7b6-efc6-48e3-b096-73a858287048">

To access the ZeroTrust network you will need an edge client, you can download it here https://openziti.io/docs/downloads

https://github.com/openziti/ziti/blob/release-next/ADOPTERS.md 


## **Contact**

- email: info@grcbit.com
- whatsapp: +1 (512) 717-7207
