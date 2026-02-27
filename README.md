# Foundations Lab: Technical Identity & Version Control

**Student Name:** Wend Tin Basile
**Course:** Cybersecurity Foundations Intensive (2026)
**Date:** February 23, 2026

## Security Philosophy <br>

This lab setup connects to core cybersecurity principles through the practices of environment standardization, system auditing, and hardware abstraction. A fundamental principle in professional cybersecurity is the creation of a standardized environment. By moving away from troubleshooting individual, varied hardware configurations (like 70 different laptops), security professionals ensure consistency and predictability with a final goal: safeguard data confidentiality, integrity and availability. In other words, this lab allows us to get to the heart of cybersecurity by starting with the CIA triad.

The **CIA Triad** is based on three principles: Confidentiality, Integrity, and Availability.
The **Confidentiality** is achieved through virtualization and logical isolation, where network segments are separated using VLANs, access control lists (ACLs), and firewall rules to restrict unauthorized access to sensitive systems and data. By deploying the lab within a virtualized environment such as Cisco Packet Tracer and isolated virtual machines, the infrastructure simulates real-world enterprise segmentation while preventing unintended external exposure. 
The Integrity is about maintaining through controlled configuration management, device authentication, and secure routing protocols that protect data from unauthorized modification. Configuration backups, hashing mechanisms, and role-based administrative access ensure that network changes are deliberate and traceable. 
The **Availability** is supported by redundancy mechanisms such as dynamic routing protocols, failover configurations, and scalable network design, which ensure that services remain operational even during device or link failures. The use of virtualization enhances availability by allowing rapid recovery, snapshot restoration, and controlled testing environments without impacting production systems. 
Together, these measures reflect a layered defense strategy aligned with established cybersecurity frameworks and best practices (National Institute of Standards and Technology [NIST], 2020; Stallings & Brown, 2018).


**AAA Framework**
Authentication, authorization, and accounting (AAA) is a security framework that controls access to computer resources, enforces policies, and audits usage. AAA and its combined processes play a major role in network management and cybersecurity by screening users and keeping track of their activity while they are connected, aligning with the principles of the CIA triad to ensure data security. (What is AAA Security?. Fortinet. (n.d.). https://www.fortinet.com/resources/cyberglossary/aaa-security) <br>

**Governance effect on cybersecurity**
Governance affects cybersecurity roles by establishing the strategic direction, assigning specific responsibilities across the organization, and bridging the gap between technical operations and senior leadership. Cybersecurity governance is essential for keeping sensitive data and digital assets safe from cyber threats. It creates clear rules and processes to protect information and helps organizations stay prepared for new risks. (What Is Cybersecurity Governance and Why Does It Matter ?. What is cybersecurity governance and why does it matter? (n.d.). https://www.ollusa.edu/blog/what-is-cybersecurity-governance.html)  <br>

**Why is governance just as important as technical skill in cybersecurity?**
Governance is considered as important as technical skill because it provides the strategic direction, accountability, and organizational structure necessary for technical tools to be effective. While technical skills represent the "how" of security—such as hacking, scanning, or patching—governance provides the "why" and the "where," ensuring that security efforts align with business goals and legal obligations.<br>

**Which cybersecurity domain (Network, GRC, or Cloud) aligns most with today’s material?**  
GRC (Governance, Risk, and Compliance) is the material that strongly aligns with the  cybersecurity domain because it focuses on structured security frameworks, control implementation, and regulatory requirements rather than purely technical configurations.It embeds the technical aspects of cybersecurity. Topics such as the Critical Security Controls, the National Institute of Standards and Technology Cybersecurity Framework, and Payment Card Industry Data Security Standard emphasize risk management, policy development, compliance validation, and security governance processes. While AAA (Authentication, Authorization, and Accounting) has technical applications in network and identity security, within this context it functions as a control mechanism required by governance frameworks and compliance standards. Overall, the material centers on managing security through policies, controls, and regulatory alignment, which are core elements of the GRC domain.

### References

National Institute of Standards and Technology. (2020). Security and privacy controls for information systems and organizations (NIST Special Publication 800-53 Rev. 5). U.S. Department of Commerce. https://doi.org/10.6028/NIST.SP.800-53r5
Stallings, W., & Brown, L. (2018). Computer security: Principles and practice (4th ed.). Pearson.
What Is Cybersecurity Governance and Why Does It Matter ?. What is cybersecurity governance and why does it matter? (n.d.). https://www.ollusa.edu/blog/what-is-cybersecurity-governance.html
hat is AAA Security?. Fortinet. (n.d.). https://www.fortinet.com/resources/cyberglossary/aaa-security


## Executive Summary
This repository establishes a secure version-control pipeline using Git and GitHub. This deployment ensures 100% traceability of configuration changes and provides a centralized audit trail for forensic or compliance reviews.