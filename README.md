# SOC-ISO-Compliant-Ipad-Lab

## Project Overview
This project demonstrates **endpoint security, governance, and compliance** using a supervised iPad managed with **Jamf Now** and optionally **Microsoft Intune**. The lab is designed to simulate enterprise-level compliance aligned with **SOC2 and ISO 27001** standards.

### Goals
- Implement password and device security policies
- Enforce app restrictions and whitelisting
- Configure network security (Wi-Fi, VPN)
- Ensure device encryption and OS patching
- Collect inventory and compliance reports
- Test enforcement and governance controls

### Tools
- **Jamf Now** – free tier for up to 3 devices  
- **Apple Configurator 2** – device supervision  
- **Microsoft Intune** – optional free trial  
- **iMazing Profile Editor** – optional, for creating custom profiles  
- **GitHub** – repo and Kanban board for project tracking  

### SOC2 / ISO Mapping
| Control | Implementation Example |
|---------|----------------------|
| Access Control | Passcode, Auto-lock, Max failed attempts |
| Device Encryption | iPad encryption enforced |
| System Hardening | Disable Siri, AirDrop, Camera, iCloud backup |
| Network Security | Wi-Fi only, VPN enforced |
| App Control | Whitelist approved apps, restrict App Store |
| Compliance Monitoring | Jamf inventory, compliance reporting, remote wipe |

### Repository Structure
SOC2-ISO-iPad-Lab/           # Repository root
 ├── README.md               # Project overview, SOC2/ISO mapping summary
 ├── Jamf/                   # Jamf configuration profiles (.mobileconfig), scripts, screenshots
 │    ├── Profiles/
 │    └── Screenshots/
 ├── Intune/                 # Intune policies, screenshots, exported JSON/XML
 │    ├── Policies/
 │    └── Screenshots/
 ├── Docs/                   # Optional: diagrams, compliance mapping tables, workflow charts
 └── LICENSE.md              # Optional open-source license if you want to share publicly

### Showcase
- Screenshots of profiles applied
- Jamf and Intune dashboard compliance views
- Video walkthroughs (optional)
