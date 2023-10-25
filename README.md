# Botium-Toys-Security-Audit-Report
# Table of contents

1. [Introduction](#introduction)
2. [Scenario](#scenario)
3. [Audit Goals](#Audit-Goals)
4. [Internal Security Audit Workflow](#workflow)
5. [Controls Assessment](#control-assessment)
6. [Compliance Checklist](#compliance-checklist)
7. [Stakeholder Memorandum](#stakeholder-memo)
8. [Conclusion](#conclusion)

#
# Introduction <a name="introduction">

An internal security audit evaluation conducted for Botium Toys, an imaginary toy company, carried out as an integral component of both my cybersecurity portfolio and as part of the Google project. <a href='https://www.coursera.org/google-certificates/cybersecurity-certificate'>Cybersecurity Professional Certificate</a>.
   
The objective is to conduct a cybersecurity program audit for Botium Toys, with a focus on aligning existing business practices with industry standards and best practices. This audit aims to offer mitigation recommendations for identified "high-risk" vulnerabilities and outline a comprehensive strategy for enhancing the organization's security posture. The audit team is responsible for documenting their findings, creating remediation plans, and engaging with stakeholders.

# Scenario  <a name="scenario">
Botium Toys, a U.S.-based small enterprise specializing in toy development and sales, has experienced significant growth in its online presence, catering to both domestic and international customers. In response to these developments, the IT department is facing heightened demands in supporting the expanding global online market.

Recognizing the need for a comprehensive strategy to ensure business continuity, compliance, and cybersecurity, the IT department manager has initiated an internal audit. The audit's primary objectives are to enhance infrastructure security, identify and address potential risks, threats, and vulnerabilities, and ensure compliance with online payment regulations and European Union (E.U.) business standards.

To achieve these objectives, the IT manager has initiated a process that includes implementing the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF), establishing clear audit scope and goals, and conducting a thorough risk assessment. The overarching goal of this audit is to provide an informed assessment of the company's current security posture, utilizing the findings as a basis for securing approval for departmental expansion.

# Audit Goals <a name="Audit-Goals">
The key goals of the internal IT audit for Botium Toys were:

-   Ensuring alignment with the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF).
-   Establishing an enhanced protocol to guarantee compliance with pertinent regulations.
-   Reinforcing system controls.
-   Applying the principle of least permissions to manage user credentials.
-   Development and implementation of policies, procedures, and playbooks.
-   Verifying adherence to pertinent standards, including GDPR, PCI DSS, and SOC1/SOC2.
   
## Internal Security Audit Workflow  <a name="workflow">
The internal security audit can be divided into two segments, each with its own set of steps to be adhered to.

### Part 1
-   Analyze the audit scope, audit goals, and risk assessment
-   Conduct the Audit
   - Satisfy the Controls assessment 
   - Select controls needing to be implemented for superior security.
   - Rate each selected control on prioirty while indicating Whether it necessitates immediate execution or can be dealt with at a later time.
   - Fulfill the Compliance Checklist and provide a rationale for the chosen compliance regulations and standards that must be followed.

### Part 2
- Review results and deliverables completed in Part 1, Step #2
- make detailed notes of findings
- contemplate the means to present your recommendations in a manner that is both clear and succinct to stakeholders. 
- Deliver the findings and recommendations to stakeholders using a brief and well-organized format

Controls Assessment  <a name="control-assessment">
===================


Current Assets 
--------------

Assets managed by the IT Department include:

- On-premises equipment for in-office business needs 

- Employee equipment: end-user devices (desktops/laptops, smartphones), remote workstations, headsets, cables, keyboards, mice, docking stations, surveillance cameras, etc.

- Management of systems, software, and services: accounting, telecommunication, database, security, ecommerce, and inventory management

- Internet access

- Internal network

- Vendor access management

- Data center hosting services 

- Data retention and storage

- Badge readers

- Legacy system maintenance: end-of-life systems that require human monitoring

# Administrative Controls 
| Control Name | Control type and explanation | Needs to be implemented (X) | Priority |
| --- | --- | --- | --- |
| Least Privilege | Preventative; reduces risk by making sure vendors and non-authorized staff only have access to the assets/data they need to do their jobs | X | High |
| Disaster recovery plans | Corrective; business continuity to ensure systems are able to run in the event of an incident/there is limited to no loss of productivity downtime/impact to system components, including: computer room environment (air conditioning, power supply, etc.); hardware (servers, employee equipment); connectivity (internal network, wireless); applications (email, electronic data); data and restoration | X | High |
| Password policies | Preventative; establish password strength rules to improve security/reduce likelihood of account compromise through brute force or dictionary attack techniques | X | High |
| Access control policies | Preventative; increase confidentiality and integrity of data | X | High |
| Account management policies | Preventative; reduce attack surface and limit overall impact from disgruntled/former employees | X | High |
| Separation of duties | Preventative; ensure no one has so much access that they can abuse the system for personal gain | X | High |

# Technical Controls 
| Control Name | Control type and explanation | Needs to be implemented (X) | Priority |
| --- | --- | --- | --- |
| Firewall | Preventative; firewalls ***are already in place*** to filter unwanted/malicious traffic from entering internal network | NA | NA |
| Intrusion Detection System (IDS) | Detective; allows IT team to identify possible intrusions (e.g., anomalous traffic) quickly | X | High |
| Encryption | Deterrent; makes confidential information/data more secure (e.g., website payment transactions) | X | High |
| Backups | Corrective; supports ongoing productivity in the case of an event; aligns to the disaster recovery plan | X | High |
| Password management system | Corrective; password recovery, reset, lock out notifications | X | High |
| Antivirus (AV) software | Corrective; detect and quarantine known threats | X | High |
| Manual monitoring, maintenance, and intervention | Preventative/corrective; required for legacy systems to identify and mitigate potential threats, risks, and vulnerabilities | X | High |


# Physical Controls
| Control Name | Control type and explanation | Needs to be implemented (X) | Priority |
| --- | --- | --- | --- |
| Time-controlled safe | Deterrent; reduce attack surface/impact of physical threats | X | Medium/Low |
| Adequate lighting | Deterrent; limit “hiding” places to deter threats | X | Medium/Low |
| Closed-circuit television (CCTV) surveillance | Preventative/detective; can reduce risk of certain events; can be used after event for investigation | X | High/Medium |
| Locking cabinets (for network gear) | Preventative; increase integrity by preventing unauthorized personnel/individuals from physically accessing/modifying network infrastructure gear | X | High/Medium |
| Signage indicating alarm service provider | Deterrent; makes the likelihood of a successful attack seem low | X | Low |
| Locks | Preventative; physical and digital assets are more secure | X | High |
| Fire detection and prevention (fire alarm, sprinkler system, etc.) | Detective/Preventative; detect fire in the toy store’s physical location to prevent damage to inventory, servers, etc. | X | Medium |

Compliance checklist
====================

To ensure data safety and compliance, Botium Toys needs to adhere to the following standards:
     
-   General Data Protection Regulation (GDPR)
      - GDPR, a comprehensive European Union (E.U.) data regulation, serves to safeguard the processing of data belonging to E.U. citizens, preserving their privacy rights both within and beyond the E.U. borders. Furthermore, in the event of a breach compromising an E.U. citizen's data, a mandatory 72-hour notification period is required.
        
- PCI DSS stands as a global security standard designed to guarantee that organizations engaged in the storage, acceptance, processing, and transmission of credit card data maintain a secure operational environment. 

    - Botium Toys is obligated to conform to PCI DSS standards due to its online and in-person payment processing, as well as its global storage and handling of customer credit card information. The organization must place significant emphasis on compliance given the potential repercussions. Non-compliance with this standard could lead to considerably more severe consequences, including monthly monetary fines, expenses associated with forensic audits in the event of a data breach, constraints from payment brands, harm to the brand's reputation, and the potential for lawsuit costs in the aftermath of data breaches.


-   System and Organizations Controls (SOC type 1, SOC type 2)
   - SOC1 and SOC2 reports serve as comprehensive assessments of an organization's user access policies across various organizational tiers. These reports not only evaluate financial compliance and risk levels but also encompass a wide array of aspects such as confidentiality, privacy, integrity, availability, security, and the overall safeguarding of data. Failures in controlling these aspects may expose an organization to the risk of fraudulent activities.   

# Stakeholder memorandum <a name="stakeholder-memo">

TO: IT Manager, Stakeholders

FROM: Eliel Cognet\
DATE: 10/24/2023\
SUBJECT: Discoveries and Suggestions from the Internal IT Audit

Dear Colleagues,

Kindly examine the provided details pertaining to the internal audit scope, objectives, significant findings, summary, and recommendations for Botium Toys.

### Scope:

- The following systems fall within the audit scope: accounting, endpoint detection, firewalls, intrusion detection systems, and the security information and event management (SIEM) tool. These systems will undergo evaluation for:

  - Current user permissions

  - Current implemented controls

  - Current procedures and protocols

- Verifying that existing user permissions, controls, procedures, and protocols are in accordance with GDPR, PCI DSS, and compliance mandates.

- Verify the accurate tracking of existing technology and assets, encompassing both hardware and system access.

### Goals:

- Comply to the NIST CSF.

- Implement an improved system procedure to guarantee compliance.

- Incorporate the principle of minimal permissions in user credential management.
  
- Enhance system controls

- Formulate their policies and procedures, encompassing their playbooks.

### Critical findings** (must be addressed immediately!):

 Multiple controls need to be developed and implemented to meet the audit goals, including:

- Separation of duties & Principle of Least Privilege 

- Start a foundation of Disaster recovery plans

- Implementation of a Password management system & a Antivirus (AV) software

- Complex Passwords, Access control, and Account management policies

- Intrusion Detection System (IDS)

- Manual monitoring, maintenance, and intervention for legacy systems

- Closed-circuit television (CCTV) surveillance along with locks and locking cabinets with any gear for the network

### It is crucial to establish and implement policies for the following:

  - To comply PCI DSS and GDPR compliance requirements.

  - To follow SOC1 and SOC2 guidance related to user access policies and all data safety.

### Findings (should be addressed, but no immediate need):

The following physical controls warrant consideration in the future, once the critical issues have been addressed:

- Time-controlled safe

- Adequate lighting

- Signage indicating alarm service provider for restricted areas

### Summary/Recommendations:

It is advisable to prioritize the prompt resolution of critical compliance issues associated with PCI and GDPR, especially given Botium Toys' expansion into international markets and the inclusion of European Union customer data. To align with the audit's objective of implementing the principle of least privilege, it is recommended to utilize SOC1 and SOC2 guidelines as a framework for developing the necessary policies and procedures related to user access.

To ensure the physical security of assets, it is strongly advised to install locks, CCTV surveillance, and a time-controlled safe. Additionally, improving the lighting and prominently displaying signage indicating the presence of alarm service providers will further fortify the overall security.

The integration of IDS and AV software into the current systems will bolster the capacity to identify intrusions, recognize potential threats, and mitigate them. This will be done while acknowledging the necessity for manual monitoring and intervention in legacy systems.

Inclusion of disaster recovery plans and backup solutions is highly advisable, as they play a pivotal role in ensuring business continuity in the face of various incidents, encompassing physical disasters like fires, as well as the most severe scenarios such as cyberattacks or technical disruptions that may impede business operations. Additionally, it is worth exploring fire detection and prevention systems as a protective measure against physical threats. These components are essential elements of a comprehensive data and system resilience strategy to safeguard the integrity and continuity of business operations.
   
# Conclusion  <a name="conclusion">
This marks the conclusion of my simulated security audit report. I hope you found it useful and enlightening as I have. Please feel free to share any constructive feedback or suggestions for refinement should they arise.

# Lessons learned:   
   Through this experience, I've come to appreciate the significance of clarity and brevity when communicating findings in stakeholder memoranda. Furthermore, I've honed my capacity to illustrate the comprehensive applicability of the System and Organizations Controls standard to diverse facets of organizational security and risk assessment, extending beyond financial compliance, an aspect I initially found challenging.
