# Ethical Hacking Mini Project — Elewayte Externship

**Author:** Pawan Kumar V
**Program:** Elewayte Ethical Hacking Externship — Mini Project
**Target:** [testphp.vulnweb.com](http://testphp.vulnweb.com/) — Acunetix's official intentionally-vulnerable test application

## Overview
This repository contains a web application penetration testing report for `testphp.vulnweb.com`, a deliberately vulnerable PHP application maintained by Acunetix for security testing practice. Five vulnerabilities were identified and documented following a professional pentest report format.

## Findings Summary

| # | Finding | Location | Severity |
|---|---|---|---|
| 1 | UNION-based SQL Injection | `artists.php?artist=` | Critical |
| 2 | SQL Injection — Authentication Bypass | `userinfo.php` (login) | Critical |
| 3 | Reflected XSS | `search.php` | High |
| 4 | Stored XSS | `guestbook.php` | High |
| 5 | Open Redirect | `redir.php?r=` | Medium |

Each finding in the report includes: vulnerability description, vulnerable URL and parameters, payload used, step-by-step Proof of Concept, business impact, remediation guidance, and references.

## Files
| File | Description |
|---|---|
| `Vulnweb_Pentest_Report.docx` | Full report (Word format) |
| `Vulnweb_Pentest_Report.pdf` | Full report (PDF format) |

## Ethics & Authorization
All testing was performed exclusively against `testphp.vulnweb.com`, which Acunetix explicitly provides and authorizes for security testing and educational practice. No other systems were tested. This report is for educational purposes as part of the Elewayte Ethical Hacking externship program.

## Skills Demonstrated
Web application penetration testing · SQL Injection (UNION-based & authentication bypass) · Cross-Site Scripting (reflected & stored) · Open redirect analysis · Vulnerability reporting · Business risk communication
