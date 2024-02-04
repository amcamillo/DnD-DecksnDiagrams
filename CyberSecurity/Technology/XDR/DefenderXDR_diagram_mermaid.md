# Defender XDR Overview in mermaid.live format

```
flowchart TD
    root("Microsoft XDR")
    
    root --> MDE("Microsoft Defender for Endpoint")
    MDE --> MDElist
    MDElist[" ✅ [Threat & Vulnerability Management]    
            ✅ [Attack Surface Reduction]
            ✅ [Next-Generation Protection]
            ✅ [Endpoint Detection and Response]
            ✅ [Automated Investigation and Remediation]
            ✅ [Secure Score for Devices]
            ✅ [Advanced Hunting] 
            ✅ [APIs for Custom Solutions and Integration] 
            ✅ [Sandboxing] 
            ✅ [Threat Analytics]"]

    root --> MDFI("Microsoft Defender for Identity")
    MDFI --> MDFIlist
    MDFIlist["
     ✅ [Automated Behavioral Analytics]
            ✅ [Identity Security Posture Assessments]
            ✅ [Advanced Threat Detection & Investigation]
            ✅ [Custom Detection]
    "]

    root --> MDO365("Microsoft Defender for Office 365")
    MDO365 --> mdolist
    mdolist["
    ✅ [Threat Protection Policies]
            ✅ [Safe Attachments]
            ✅ [Safe Links]
            ✅ [Anti-phishing Protection]
            ✅ [Real-time Detection]
            ✅ [Automated Investigation and Response]
            ✅ [Attack Simulator]
            ✅ [Threat Tracker]
            ✅ [Threat Explorer]
            ✅ [Reports and Insights]
    "]

    root --> MDFCA("Microsoft Defender for Cloud Apps")
    MDFCA --> mdcalist
    mdcalist["
     ✅ [App Discovery]
            ✅ [Data Protection and Loss Prevention]
            ✅ [Threat Protection]
            ✅ [Anomaly Detection]
            ✅ [SSPM - SaaS Security Configuration Management]
            ✅ [Conditional Access App Control]
            ✅ [SaaS Services Risk Assessment]
            ✅ [App Governance]

    "]

    root --> EID("Entra ID")
    EID --> idlist
    idlist["
    ✅ [Privileged Identity Management]
    ✅ [Conditional Access]
    ✅ [Risk-based Conditional Access]
    ✅ [Identity Protection]
    ✅ [Multi-Factor Authentication (MFA)]
    ✅ [Passwordless Authentication]
    ✅ [Access Reviews]
    ✅ [Entitlement Management]
    ✅ [Identity Secure Score]
    ✅ [Application Management]
    ✅ [B2B (Business-to-Business) Identity Services]
    ✅ [B2C (Business-to-Consumer) Identity Services]
    ✅ [Identity Governance]
    "]

    root --> purds("Microsoft Purview Data security")
    purds --> purdslis
    purdslis["
    
    "]


%%    root --> EID("Entra ID")
%%    EID --> idlist
%%    idlist["
%%    ✅ [Identity Governance]
%%    ✅ [Privileged Identity Management]
%%    ✅ [Conditional Access]
%%    ✅ [Identity Protection]
%%    ✅ [Multi-Factor Authentication (MFA)]
%%    ✅ [Passwordless Authentication]
%%    ✅ [Access Reviews]
%%    ✅ [Entitlement Management]
%%    ✅ [Identity Secure Score]
%%    ✅ [Application Management]
%%    ✅ [B2B (Business-to-Business) Identity Services]
%%    ✅ [B2C (Business-to-Consumer) Identity Services] 
%%    "]
```
