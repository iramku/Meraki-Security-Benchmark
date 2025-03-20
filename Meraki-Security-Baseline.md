# CIS 18 Mapping to Cisco Meraki 

## CIS Control 1: Inventory and Control of Enterprise Assets
Meraki Dashboard & Systems Manager: Provides visibility into all connected devices, including wired and wireless clients.
Network Access Control (NAC) via Meraki Access Policies: Can help control unauthorized devices.

## CIS Control 2: Inventory and Control of Software Assets
Meraki Systems Manager (MDM/EMM): Allows software inventory management on enrolled devices.
App Whitelisting & Blacklisting: Enforce policies on which applications can be installed or run.

## CIS Control 3: Data Protection
Meraki Auto VPN & Site-to-Site VPN: Encrypts data in transit.
Group Policies & Firewall Rules: Restricts access to sensitive data.
Layer 7 Application Control: Blocks unauthorized data exfiltration attempts.

## CIS Control 4: Secure Configuration of Enterprise Assets and Software
Meraki Security Appliance (MX) & Cloud-Managed Updates: Ensures latest security updates.
Auto Patching & Firmware Management: Automatic updates across devices.

## CIS Control 5: Account Management
Meraki Dashboard SSO & MFA: Ensures secure authentication.
Role-Based Access Control (RBAC): Limits user permissions based on roles.

## CIS Control 6: Access Control Management
Identity-Based Policies (802.1X, RADIUS Integration): Controls access based on identity.
Layer 7 Firewall Rules & Group Policies: Restricts access to enterprise assets.

## CIS Control 7: Continuous Vulnerability Management
Security Center & Network Health Analytics: Identifies vulnerabilities and performance issues.
Malware Protection (Advanced Security License for MX): Blocks known exploits and malware.

## CIS Control 8: Audit Log Management
Meraki Dashboard Logs & Syslog Integration: Centralized logging for security monitoring.
Alerts & Notifications: Detects and reports suspicious activities.

## CIS Control 9: Email and Web Browser Protections
Cisco Umbrella Integration with Meraki: Provides DNS-based filtering for phishing and malware protection.
Layer 7 Firewall & Content Filtering: Blocks malicious websites.

## CIS Control 10: Malware Defenses
Cisco AMP & Threat Grid Integration (MX with Advanced Security): Provides real-time malware protection.
Content Filtering & Antivirus Scanning: Blocks suspicious file downloads.

## CIS Control 11: Data Recovery
Cloud-Based Backup Solutions & Redundant Configuration: Provides failover options.
Auto VPN Failover & Redundancy: Ensures continuity in case of failure.

## CIS Control 12: Network Infrastructure Management
Cloud-Based Centralized Management via Meraki Dashboard: Simplifies network management.
Zero Trust & Least Privilege Network Design: Implements access segmentation.

## CIS Control 13: Network Monitoring and Defense
Security Center & Intrusion Detection/Prevention (IDS/IPS) (MX): Monitors network traffic for threats.
NetFlow & Traffic Analytics: Helps in threat detection and response.

## CIS Control 14: Security Awareness and Skills Training
Security Reports & Alerting: Provides insights to help IT teams educate users.
Security Policies & Access Control Enforcement: Ensures compliance with security training policies.

## CIS Control 15: Service Provider Management
Third-Party API Integrations & Monitoring: Ensures service provider compliance.
Meraki Trust Center: Provides transparency on security policies.

## CIS Control 16: Application Software Security
Cisco Umbrella & Cloud Security Integration: Protects applications from threats.
Layer 7 Application Control & Web Filtering: Restricts access to risky applications.

## CIS Control 17: Incident Response Management
Security Alerting & Automated Threat Response: Helps in early detection and mitigation.
Event Logging & Syslog Export: Supports incident investigation.

## CIS Control 18: Penetration Testing
Built-in Security Features & External Pen Testing Support: Meraki MX devices can work with external security assessments.
Security Event Monitoring & Threat Analytics: Identifies attack vectors.
