# Security Principles

## Learning Objectives:
- Understand the CIA Triad and its importance.
- Explain Risk, Privacy, and Accountability.
- Relate security principles to real-world cyber incidents.

## CIA Triad
- The CIA Triad forms the foundation of information security.
- Each element ensures that information remains safe and trustworthy.

| Element | Description | Example |
|----------|--------------|----------|
| Confidentiality | Ensures data is accessible only to authorized users. | Encrypting files, using passwords, access control lists. |
| Integrity | Ensures data is accurate, consistent, and not tampered with. | Using hashing, digital signatures, checksums. |
| Availability | Ensures systems and data are available when needed. | Redundant servers, backups, DDoS protection. |

![download](https://github.com/user-attachments/assets/c390aa1e-d6c3-4d66-b664-8fc71d53aacc)


## Key Concepts
- Data breaches often occur when one or more CIA principles are compromised.
- Balance is key — too much focus on one (e.g., availability) can weaken another (e.g., confidentiality).


## Examples
- Confidentiality Violation: Unauthorized access to customer data (e.g., Facebook–Cambridge Analytica case).
- Integrity Violation: Tampered medical data in hospitals leading to misdiagnosis.
- Availability Violation: DDoS attack on banking websites preventing service access.

## Risk, Privacy, and Accountability

### Risk
- Definition: Probability of a threat exploiting a vulnerability to cause harm.

### Components
- Threat: Something that can cause damage.
- Vulnerability: Weakness that can be exploited.
- Impact: Damage if threat is realized.

### Formula
Risk = Threat × Vulnerability × Impact

### Example
- Threat: Phishing  
- Vulnerability: Employee lack of awareness  
- Impact: Credential theft, financial loss




<img width="259" height="194" alt="download" src="https://github.com/user-attachments/assets/059236d2-fd2e-4b18-8a6d-56db33eb1981" />







## Privacy
- Protecting personal and sensitive information of individuals.
- Governed by laws like GDPR, DPDP Act (India), HIPAA.



![download](https://github.com/user-attachments/assets/dd583d49-d26e-4ac7-b6ef-e3614c5218d9)





### Key Practices:
- Data minimization  
- Informed consent  
- Data anonymization  

Example: A healthcare app must not share user health data without consent.

## Accountability
- Ensuring every action in an IT system can be traced back to an individual.

### Achieved through:
- Logging & auditing  
- User access tracking  
- Non-repudiation mechanisms  

Example: Audit logs in firewalls to trace malicious user actions.


## 🌍 Real-World Case Studies

| Case | Description | Violated Principle |
|------|--------------|--------------------|
| WannaCry (2017) | Ransomware disabled hospital systems worldwide | Availability |
| Equifax Breach (2017) | Personal data of 143M users leaked | Confidentiality & Integrity |
| Twitter Hack (2020) | Insider access to admin tools | Confidentiality & Accountability |
