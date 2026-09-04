# "Hands-on Linux and cybersecurity labs."
Documenting all my cybersecurity journey
practiced changing file permission with chmod and chown
and i noticed users and groups affect access
# lab 2 wireshark basics
## capturing network traffics with wireshark
what i saw, DNS lookups and some TCP handshake 
## what i learned, basic response  
# Lab 3: Basic SQL Data Querying.
## What I practiced was using a sample employees table to write queries and get comfortable with basic SQL syntax. Queries, first, display all records with SELECT* FROM employees. Expected result shows every row and column.
i did SELECT* first_name, last_name FROM employees. Expected result shows only those two columns.
Also did, filter by department using WHERE department equals IT. Expected result returns only IT staff.
Also, find employees with salaries greater than 65,000. Expected result lists only higher earners.
lastly, sort by salary descending using ORDER BY salary DESC. Expected result shows employees from highest to lowest pay
this was what i learned today
# VULNERABILITY ASSESSMENT
## Performed a vulnerability assessment on a Linux database server using NIST methodology. Identified threats, rated likelihood and severity, and recommended practical mitigations.” then add one line like "Reinforced the importance of not hard-coding secrets in applications.
# Vulnerability Assessment: E-commerce Database Server

## Overview
A qualitative vulnerability assessment of an e-commerce company's
publicly accessible remote database server.

## Objectives
- Identify potential threat sources
- Identify relevant threat events
- Assess likelihood and severity
- Calculate overall risk
- Recommend remediation controls

## Framework
NIST SP 800-30 Rev. 1

## Risk Assessment

| Threat | Likelihood | Severity | Risk |
|---|---:|---:|---:|
| Unauthorized database access | 3 | 3 | 9 |
| Malicious insider activity | 2 | 3 | 6 |
| Denial-of-service attack | 2 | 3 | 6 |

## Recommended Controls
- Network access restrictions
- Principle of least privilege
- Multi-factor authentication
- Encryption
- Logging and monitoring
- Defense in depth
- Regular vulnerability assessments
- Secure backups

## Conclusion
The publicly accessible database represents a critical security risk.
Restricting database exposure and implementing layered security controls
would significantly reduce the likelihood and impact of compromise.
# USB Baiting Attack — Cybersecurity Risk Assessment

## Overview
A cybersecurity risk assessment examining the risks associated with
an unknown USB drive containing personal and organizational information.

## Scenario
A USB drive belonging to an HR manager at a hospital is discovered.
The drive contains both personal and work-related files.

## Key Risks
- USB baiting
- Malware introduction
- Social engineering
- PII exposure
- Unauthorized access
- Information leakage

## Attacker Mindset
[Your Attacker Mindset section]

## Risk Analysis
[Your Risk Analysis section]

## Recommended Controls
- USB device controls
- Endpoint protection
- Malware scanning
- Security awareness training
- Encryption
- Access controls
- Separation of personal and business USB devices

## Conclusion
Unknown removable media should be treated as untrusted. Combining
technical controls, employee awareness, and organizational policies
can significantly reduce the risk associated with USB baiting attacks.
