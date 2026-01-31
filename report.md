# Firewall Configuration and Logging Report  
**Task 10 – UFW Firewall Analysis**

---

## Target Environment
- Operating System: Kali Linux
- Firewall Tool: UFW (Uncomplicated Firewall)
- Environment Type: Local Lab Setup

---

## Objective
The purpose of this task is to understand how firewall rules are applied,
how logging works, and how firewall configurations help protect a system
from unauthorized access.

---

## Firewall Status Review
The firewall utility was checked to determine whether it was installed
and active on the system. Firewall rules were reviewed to understand
default allow and deny behaviors.

---

## Firewall Logging
Firewall logging was enabled to record traffic decisions made by the
firewall. This helps administrators monitor blocked or allowed
connections and identify suspicious activity.

---

## Firewall Rules Analysis
Firewall rule definitions were reviewed from the firewall rules file.
These rules define:
- Allowed inbound connections
- Denied inbound connections
- Default firewall behavior

The rules reflect standard security practices used to reduce attack
surface.

---

## Observations
- Firewall rules are effective in filtering network traffic.
- Logging provides visibility into firewall activity.
- Missing or restricted log files are common in hardened systems.
- Firewall configuration plays a critical role in system security.

---

## Security Impact
Proper firewall configuration significantly reduces exposure to network
attacks. Logging further enhances security by enabling auditing and
incident investigation.

---

## Conclusion
This task successfully demonstrated firewall configuration and logging
using UFW. Understanding firewall rules and logs is essential for
maintaining a secure Linux environment.
