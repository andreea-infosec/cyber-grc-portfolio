# Control Mapping – ISO 27001 & NIST CSF

This document maps identified cyber risks to relevant controls from ISO 27001 and the NIST Cybersecurity Framework (NIST CSF).
The mapping is selective and risk-based, and is not intended to represent full compliance with either framework.

---

## Risk R-001 – Credential Compromise / Phishing

**Risk summary**  
Unauthorized access to customer data due to compromised user credentials.

### ISO 27001 (Annex A)
- A.9.2 – User access management  
- A.7.2 – Information security awareness, education and training  
- A.12.4 – Logging and monitoring  

**Rationale**  
These controls reduce the likelihood of unauthorized access and support detection of anomalous authentication activity.

### NIST CSF
- Protect (Access Control, Awareness and Training)  
- Detect (Anomalies and Events, Security Monitoring)

---

## Risk R-002 – Third-Party / Vendor Breach

**Risk summary**  
Unauthorized disclosure of customer data due to a security breach at a third-party service provider.

### ISO 27001 (Annex A)
- A.15.1 – Information security in supplier relationships  
- A.15.2 – Supplier service delivery management  
- A.8.2 – Information classification  

**Rationale**  
These controls govern how supplier security risks are identified, assessed, and monitored throughout the vendor lifecycle.

### NIST CSF
- Identify (Supply Chain Risk Management)  
- Protect (Data Protection Processes)

---

## Risk R-003 – Cloud Misconfiguration

**Risk summary**  
Unauthorized access or exposure of customer data due to misconfigured cloud infrastructure or access controls.

### ISO 27001 (Annex A)
- A.12.1 – Operational procedures and responsibilities  
- A.9.1 – Business requirements of access control  
- A.12.4 – Logging and monitoring  

**Rationale**  
These controls support secure configuration management, access governance, and detection of configuration drift in cloud environments.

### NIST CSF
- Protect (Configuration Management, Access Control)  
- Detect (Continuous Monitoring)
