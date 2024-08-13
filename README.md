# **grc4ciso (GRC + XDR + GPT + ZT)**

### **Introduction**

grc4ciso integrates GRC, XDR, Zero Trust and GPT cybersecurity capabilities into a unified Software-as-a-Service (SaaS) platform.

This platform provides you:

- Governance, Risk, and Compliance (**GRC**): this is a community module hosted by OWASP projects https://github.com/OWASP/www-project-it-grc 
- Extended Detection and Response (**XDR**): endpoint security, configuration assessment, malware detection, file integrity monitoring, threat Intelligence, log data analysis, vulnerability detection, security operations, incident response, regulatory compliance, cloud security, container security.
- **GPT-4** assistant: GPT virtual CISO assistant integrated into the GRC module to provide you advise about cybersecurity activities, the GPT-4 assistant is also integrated into the XDR module to provide you information about the endpoints connected.
- **Zero Trust**: provide you the required components to implement a zero trust overlay network to protect web applications and services.

**With this platform you can get the power of these cybersecurity tools into a single SaaS platform!!**

<img width="527" alt="grc4ciso_1" src="https://github.com/grcbit/grc4ciso/assets/60721087/b9ece702-c369-40e5-98b2-4199330e3b58">

## **GRC (Governance, Risk and Compliance)**

Visit https://github.com/OWASP/www-project-it-grc

### **Aditional enterprise features**

### **Compliance**

Pre-mapped ISO27001:2022 controls so you can focus on statement of applicability.

Also stay compliant with the following frameworks:

- PCI DSS 4.0
- NIST 800-53-V1
- CIS Controls V8
- NIST CSF 2.0
- NIST CSF 1.1
- OWASP ASVS 4.0.3
- You can load more frameworks if you need it.

### **Employee Awareness**

- You can launch security awareness campaigns, and track the user's response.

<img width="749" alt="image" src="https://github.com/grcbit/grc4ciso/assets/60721087/9b87d61d-6e77-4a1c-9493-3f1b2b9ba84e">

- Also you can plan onboarding and offboarding employee security activities.


## **XDR**

XDR functionalities are based on wazuh platform, Wazuh is a free and open source platform used for threat prevention, detection, and response. It is capable of protecting workloads across on-premises, virtualized, containerized, and cloud-based environments.

Wazuh solution consists of an endpoint security agent, deployed to the monitored systems, and a management server, which collects and analyzes data gathered by the agents. Besides, Wazuh has been fully integrated with the Elastic Stack, providing a search engine and data visualization tool that allows users to navigate through their security alerts.

**With grc4ciso you can increase the power of this tool, because you can analize the data generated by the XDR with GPT-4, and you can register the incidents identified, define containment and recovery actions from an attack.**
**Having all these functionalities in the same platform give more capabilities to protect your data combining GRC + GPT + XDR + Zero Trust camabilities.**

<img width="941" alt="image" src="https://github.com/grcbit/grc4ciso/assets/60721087/13252dea-d3c5-4fba-9022-98c154b9b7ec">


## **GPT-4**

**grc4ciso** integrates a **GPT assistant** that is trained to advised you on Cybersecurity activities, so you have a virtual CISO helping you to manage cybersecurity activities all time you need it.

<img width="874" alt="image" src="https://github.com/grcbit/grc4ciso/assets/60721087/e04d77a0-50f9-4910-b63b-1c7ff90ed363">


Also if you are using the **XDR** module, the assistant can give you information about the endpoints that are connected to your **XDR**, so, you can for example ask the **grc4ciso GPT assistant** to summarize the main vulnerabilities you have in your systems, so you can take needed actions to mitigate cybersecurity risks.

You can also ask to grc4ciso GPT to create a threat scenario based on vulnerabilities identified and ask for recommendations to mitigate risks.

XDR GPT Assistant Examples:

- Show me the list of agents that are integrated to the XDR.
  
- <img width="542" alt="image" src="https://github.com/grcbit/grc4ciso/assets/60721087/b56d1b8a-f66c-4c45-bc0c-146200fb8a1b">

- Show me the vulnerabilities of the agent {agent_id}.
  
- <img width="503" alt="image" src="https://github.com/grcbit/grc4ciso/assets/60721087/1519382c-4a23-419d-8201-a0921fca1b2e">

- Based on {agent_id} vulnerabilities create a threat scenario.

- <img width="734" alt="image" src="https://github.com/grcbit/grc4ciso/assets/60721087/d6a30f5a-000d-4be1-adcb-76fdaec4935b">

- What I need to do to mitigate vulenrability CVE-2023-50387 detected in the {agent_id}.

- <img width="866" alt="image" src="https://github.com/grcbit/grc4ciso/assets/60721087/a87c5c6e-6f20-4891-bdff-626faa6a27d7">

- Show me the configuration of the agent {agent_id}.
- Show me the key of the agent {agent_id}.
- Summarize the operating systems of the agents.
- Summarize the status of the agents.
- Show me the CISCAT (Center for Internet Security Configuration Assessment Tool) scan results of the agent {agent_id}.
- Show me ports open of the agent {agent_id}.
- Show me the packages that are installed in the agent {agent_id}.
- Show me the operating system of the agent {agent_id}.
- Show me the network information of the agent {agent_id}.
- Show me the hotfixes installed in the agent {agent_id}.
- Show me the hardware information of the agent {agent_id}.
- Show me the results of the configuration assessment of the agent {agent_id}

You can also try the GPT https://chat.openai.com/g/g-NQR7ndLer-grc4ciso 






## **ZeroTrust**

grc4ciso provides you all the needed components to create a Zero Trust network to protect you web applications and services, it is based on the openziti platform. OpenZiti is a free and open source project focused on bringing zero trust networking principles directly into any application. The project provides all the pieces required to implement a zero trust overlay network and provides all the tools necessary to integrate zero trust into your existing solutions. 

<img width="884" alt="image" src="https://github.com/grcbit/grc4ciso/assets/60721087/5203d7b6-efc6-48e3-b096-73a858287048">

To access the ZeroTrust network you will need an edge client, you can download it here https://openziti.io/docs/downloads

https://github.com/openziti/ziti/blob/release-next/ADOPTERS.md 

### **grc4ciso Security**

grc4ciso provide the following security functionalities:

- XDR module is protected with Zero Trust, it mandates authentication and authorization before any connectivity can be established using a strong identity.
- Multi-factor authentication can be enable to authenticate to the GRC platform.
- The authorization to the grc4ciso components and functionalities are restricted by roles and privileges, so each user only can access the resources needed for their functions.

### **grc4ciso roles**
R - Read, W - Write, C - Create, U - Unlink

|         | Asset Management | ISMS | Risk Management| Control | Compliance | Settings|
| --------|-------------|-------|------------|------------|------------|------------|
| GRC Admin | RWCU | RWCU | RWCU | RWCU | RWCU | RWCU |
| GRC Consultant |RWCU|RWCU|RWCU|RWCU|RWCU|RWCU|
| Asset Management|RWCU|R|R|R|R|R|
| ISMS |R|RWCU|R|R|R|R|
| Risk Management|R|R|RWCU|R|R|R|
| Control|R|R|R|RWCU|R|R|
| Compliance |R|R|R|R|RWCU|R|
| Guest|R|R|R|R|R|R|

### DEMO




### Contact

- email: contacto@grcbit.com
- whatsapp: +52 44-39-02-87-96
