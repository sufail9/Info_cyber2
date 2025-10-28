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

![download](https://github.com/user-attachments/assets/70ea8586-d629-438e-b78b-2b6f6738b787)

# Key Concepts
- Data breaches often occur when one or more CIA principles are compromised.
- Balance is key - too much focus on one (e.g., availability) can weaken another (e.g., confidentiality).
# Examples
- *Confidentiality Violation:* Unauthorized access to customer data (e.g., Facebook-Cambridge Analytica case).
- *Integrity Violation:* Tampered medical data in hospitals leading to misdiagnosis.
- *Availability Violation:* DDoS attack on banking websites preventing service access.

# Risk, Privacy, and Accountability
# Risk
- *Definition:* Probability of a threat exploiting a vulnerability to cause harm.

## Components:
- *Threat* -> something that can cause damage.
- *Vulnerability* -> weakness that can be exploited.
- *Impact* -> damage if threat is realized

## Formula:
- *Risk = Threat x Vulnerability x Impact*
## Example:
- *Threat:* Phishing
- Vulnerability: Employee lack of awareness
-  Impact:Credential theft,financial loss
  
![download](https://github.com/user-attachments/assets/777caef4-0b45-4090-bd1d-16128cf13ed6)



# Privacy
- protecting personal and sensitive information of individuals
- Governed by Laws lik GDPR,DPDP Act (India),HIPAA.


![download](https://github.com/user-attachments/assets/9a090ef0-3074-4c09-a558-c4a652353420)


## key practices:
- Data minimization
- Informed consent
- Data anonymization

Example: A healthcare app must not share user health data without consent

# Accountability
Ensuring every action in an IT system can be traced back to an induvidual.

## Achieved through:
- Logging & auditing
- Using access tracking
- Non-repudiation mechanisms

Example:Audit logs in firewalls to trace malicious user actions.

|        Case                  |           Description                           |           Violated Principle |
| ------------------ | ----------------------------------------------------- | ---------------------------------------------------- |
|WannaCry (2017)               | Ransomware disabled hospital systems worldwide  | Availability                 |
|Equifax Breach (2017)         | Personal data of  143M users leaked             | Confidentiality & Integrity|
|Twiter Hack (2020)            | Insider access to admin tools                   | Confidentiality & Accountability|
