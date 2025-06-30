## Conductiong an internal Security Audit

A cybersecurity internal security audit is a systematic evaluation of an organization's security controls, policies, and procedures related to its information systems and data. It's conducted by the organization's internal audit team to identify vulnerabilities, assess compliance with security standards, and improve the overall security posture. n simple terms, internal audits ensure that security checks are performed to monitor potential threats, risks, and vulnerabilities that could affect an organization’s business continuity and its critical assets.

The purpose of a security audit is to determine if the information systems in your company comply with internal or external standards that govern infrastructure, network, and data security. The IT rules, practices, and security controls of your business are examples of internal criteria.

For a more in-depth understanding of the key aspects of conducting a cybersecurity audit,  refer to this helpful resource:  
**https://www.geeksforgeeks.org/computer-networks/what-is-a-cyber-security-audit/** 

### Scenario 

Botium Toys is a small U.S. business that develops and sells toys. The business has a single physical location, which serves as their main office, a storefront, and warehouse for their products. However, Botium Toy’s online presence has grown, attracting customers in the U.S. and abroad. As a result, their information technology (IT) department is under increasing pressure to support their online market worldwide. 

The manager of the IT department has decided that an internal IT audit needs to be conducted. She's worried about maintaining compliance and business operations as the company grows without a clear plan. She believes an internal audit can help better secure the company’s infrastructure and help them identify and mitigate potential risks, threats, or vulnerabilities to critical assets. The manager is also interested in ensuring that they comply with regulations related to internally processing and accepting online payments and conducting business in the European Union (E.U.).   

The IT manager starts by implementing the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF), establishing an audit scope and goals, listing assets currently managed by the IT department, and completing a risk assessment. The goal of the audit is to provide an overview of the risks and/or fines that the company might experience due to the current state of their security posture.

Your task is to review the IT manager’s scope, goals, and risk assessment report. Then, perform an internal audit by completing a controls and compliance checklist. 

---

As part of the audit, I reviewed and worked with the following documents:


1. **[Botium-Toys-Scope-Goals-and-Risk-Assessment-Report](https://github.com/cherinejoseph/security-audit/blob/main/Botium-Toys-Scope-goals-and-risk-assessment-report.pdf))**  
   - **Purpose**: This document provides a comprehensive overview of the audit scope, the goals for the audit, and the risk assessment conducted by the IT department. It outlines the assets managed by the department and highlights the primary risks the company faces. I’ve carefully reviewed this document to identify the key areas for security improvement and to better understand the company’s current state.

2. **[Control-Categories](https://github.com/cherinejoseph/security-audit/blob/main/Control-categories.pdf)**  
   - **Purpose**: This document breaks down the different **control categories** needed to complete the audit. It includes areas like **access control**, **incident response**, **data protection**, and **compliance** standards. I’ve used this document as a guide to evaluate whether Botium Toys is meeting the necessary best practices and industry standards in these critical areas.

3. **[Controls-and-Compliance-Checklist](https://github.com/cherinejoseph/security-audit/blob/main/Controls-and-compliance-checklist.pdf)**  
   - **Purpose**: This checklist is where I’m inputting my findings based on the **scope report** and **control categories**. It includes questions about whether key security controls and compliance standards are in place. For each question, I’m marking "Yes" or "No" based on my analysis, and I’m also noting **recommendations** where improvements are needed.

---
## Task:
1. **Review the Scope, Goals, and Risk Assessment Report**:  
   The first step was to review the **Scope, Goals, and Risk Assessment Report** to understand the **assets** managed by the IT department, the **identified risks**, and the **goals** for the audit. This document helped provide clarity on the current state of the organization’s security and where potential improvements could be made.

2. **Use the Control Categories Document**:  
   The **Control Categories document** was then used to assess which **security controls** were already in place and which areas needed improvement. The document breaks down the critical areas of security, such as **access control**, **incident response**, and **data protection**, providing a clear framework to evaluate compliance.

3. **Complete the Controls and Compliance Checklist**:  
   Based on the information from the scope report and control categories, I completed the **Controls and Compliance Checklist**. For each control and compliance category, I answered the “Yes” or “No” questions, indicating whether the organization was meeting best practices. If the answer was “No,” I provided **recommendations** on how the organization could improve its security posture and address any vulnerabilities.


### Findings & Recommendations

- **Access Control**:
  - **Finding**: Lack of MFA for critical systems.
  - **Recommendation**: Implement **Multi-factor Authentication (MFA)** for all sensitive systems.

- **Incident Response**:
  - **Finding**: No formal incident response plan.
  - **Recommendation**: Develop a formal **Incident Response Plan (IRP)** and conduct regular **incident response training** for all relevant staff.

- **Data Protection**:
  - **Finding**: Customer data is not encrypted.
  - **Recommendation**: Implement **end-to-end encryption** for data in transit and **AES encryption** for data at rest.

- **Compliance**:
  - **Finding**: Not fully compliant with **GDPR** for EU customers.
  - **Recommendation**: Review and update data collection and processing practices to ensure full **GDPR** compliance.

 
You can view the completed Controls and Compliance checklist here:

[Completed Compliance and Controls Checiklist ](https://github.com/cherinejoseph/security-audit/blob/main/Completed-Controls-and-compliance-checklist.pdf)


 ---

## Additional Info

### Security Audit Checklist for Botium Toys

#### 1. Review the Scope, Goals, and Risk Assessment Report

- [ ] **Identify IT assets currently managed by the department.**
  - Includes: servers, customer data, financial systems, etc.
  
- [ ] **Understand the identified risks to business operations and infrastructure.**
  - Includes: potential cyber threats, vulnerabilities, regulatory compliance risks.

- [ ] **Understand the audit goals set by the IT department.**
  - Focus: security posture, risk mitigation, compliance with EU regulations (GDPR), and online payment systems.

#### 2. Review Control Categories Document

- [ ] **Access Control:**
  - [ ] Are access controls defined and enforced for critical systems and data?
  - [ ] Is there a process for managing user permissions, especially for employees with access to sensitive data?

- [ ] **Incident Response:**
  - [ ] Does Botium Toys have a documented incident response plan for cybersecurity events?
  - [ ] Is the response plan reviewed regularly and updated when needed?

- [ ] **Data Protection:**
  - [ ] Is sensitive customer data, including payment info, encrypted during storage and transmission?
  - [ ] Are there backup and recovery strategies in place to protect business-critical data?

- [ ] **Compliance:**
  - [ ] Is Botium Toys compliant with **GDPR** for EU customers’ data?
  - [ ] Are online payment systems in compliance with **PCI-DSS** standards?
  - [ ] Are there regular audits for adherence to local and international data protection laws?

#### 3. Compliance Best Practices

- [ ] **Access Control Best Practices:**
  - [ ] Are there strong password policies and authentication mechanisms (e.g., MFA) in place for employees accessing critical systems?

- [ ] **Incident Response Best Practices:**
  - [ ] Is there a plan for regularly testing the incident response process (e.g., drills)?
  - [ ] Is there a designated team or person responsible for handling security incidents?

- [ ] **Data Protection Best Practices:**
  - [ ] Are there policies to ensure **data minimization** (only storing necessary data) and **data retention** (proper disposal after use)?
  - [ ] Is sensitive customer data anonymized or pseudonymized when possible to reduce risk?

- [ ] **Compliance Best Practices:**
  - [ ] Is there a process for keeping up with changes in data protection regulations (like GDPR)?
  - [ ] Are employees trained on compliance requirements, especially regarding data protection and online payment regulations?

#### 4. Overall Audit Summary

- [ ] **Identify any immediate security gaps**: Are any controls or compliance standards significantly lacking or outdated?
- [ ] **Recommend improvements**: What changes can Botium Toys make to improve security, risk management, and compliance?

---

## **Acknowledgements**

This project was completed as part of the **Google Cybersecurity Professional Certificate** on **Coursera**. The insights gained in this course informed the process reviews and improvements presented here.

For more information about the **Google Cybersecurity Professional Certificate**, please visit [Coursera](https://www.coursera.org/professional-certificates/google-cybersecurity).














