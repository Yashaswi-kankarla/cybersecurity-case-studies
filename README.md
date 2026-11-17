# Malware Analysis Case Study

## Overview

This case study documents the static and dynamic analysis of a suspicious Windows executable and associated DLL. The investigation focused on identifying persistence mechanisms, process behavior, network communication patterns, and indicators of compromise (IOCs).

## Objectives

- Verify malware execution artifacts.
- Perform static analysis of executable and DLL components.
- Observe runtime behavior in an isolated environment.
- Identify persistence mechanisms and defense-evasion techniques.
- Analyze command-and-control (C2) communication attempts.
- Map observed behaviors to the MITRE ATT&CK framework.

## Methodology

1. Prefetch analysis to confirm execution history.
2. Static analysis of executable and DLL artifacts.
3. Hash generation and IOC collection.
4. Dynamic monitoring using process and registry analysis tools.
5. Network traffic capture and inspection.
6. Correlation of behavioral, registry, and network evidence.
7. MITRE ATT&CK mapping and reporting.

## Skills Demonstrated

- Malware Analysis
- Static Analysis
- Dynamic Analysis
- Threat Intelligence
- IOC Extraction
- MITRE ATT&CK Mapping
- Registry Forensics
- Network Traffic Analysis
- Digital Forensics
- Technical Reporting

## Key Findings

- Malware established persistence through registry modifications.
- Suspicious DLL loading and process creation activity were observed.
- Evidence of defense-evasion techniques and anti-analysis behavior.
- Encrypted outbound network communication attempts were identified.
- Multiple indicators consistent with Trojan-like behavior were documented.

## Tools & Technologies

- PEStudio
- PECmd
- Certutil
- Procmon
- Regshot
- Wireshark
- Windows 10 VM
- Oracle VirtualBox

## Outcomes

- Identified persistence mechanisms and execution artifacts.
- Extracted actionable indicators of compromise.
- Documented malicious behavior across file, registry, process, and network layers.
- Produced a comprehensive malware analysis report with remediation considerations.

## Repository Contents

- `Malware_Analysis.pdf` – Full investigation report
- Supporting screenshots and evidence contained within the report

## Disclaimer

This case study is shared for educational and portfolio purposes. Any sensitive, proprietary, or assessment-specific information has been omitted or anonymized where appropriate.
