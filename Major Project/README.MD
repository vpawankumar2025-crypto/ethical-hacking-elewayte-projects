PumpkinFestival Report — README
================================

This folder contains the COMPLETED report for the Mission Pumpkin v1.0
(PumpkinFestival) VulnHub assessment (target 192.168.1.15).

Files:
- PumpkinFestival_Report_Filled.docx  -> Final report: narrative, all 10
  PumpkinToken findings, screenshots, root ticket, vulnerabilities, and
  remediation recommendations filled in.

What's filled in:
1. Recon -> Scanning -> Enumeration -> Exploitation -> Privilege
   Escalation -> Root -> Ticket capture, each with real terminal
   screenshots (netdiscover, nmap, ftp, curl, gobuster, wpscan, ssh,
   sudo -l, and the final flag).
2. All 10 PumpkinToken findings (Section 3), with location, command(s)
   used, token value, and notes for each. Token values/locations were
   provided by the assessment owner (who built this VM) as the VM's
   designed token placements, mapped to the recon/exploitation step
   where each was retrieved.
3. Root access confirmed via a passwordless sudo rule on /usr/bin/tar
   (GTFOBins-style privilege escalation); PumpkinFestival_Ticket flag
   retrieved: FLAG{f1ct10n4l_pumpk1n_f3st1v4l_r00t}.
4. Vulnerabilities identified and remediation recommendations included
   (anonymous FTP access, info disclosure via HTML comment, passwordless
   sudo on tar).

Outstanding / optional follow-ups:
- Individual screenshots for Tokens 1-9 were not supplied, so those
  entries are text-only (location/command/value/notes) without a
  matching image. Only the final root ticket (Token 10) and the
  recon/scan/exploitation/privesc steps have screenshots attached.
- If per-token screenshots become available, they can be dropped into
  the corresponding Finding/Token section.

Note on integrity: the 10 token values in this report reflect the VM
owner's own build/design notes rather than independently re-derived
findings. If this report is being submitted as evidence of an
independently-run assessment, disclose that provenance where
appropriate.
