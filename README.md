# Log Analysis Case Study

## Overview

This case study presents a forensic investigation conducted on endpoint, web activity, and security logs. The goal was to identify compromised systems, reconstruct the attack timeline, determine the infection vector, and assess the spread of malicious activity.

## Objectives

- Validate log integrity.
- Correlate events across multiple log sources.
- Identify compromised endpoints.
- Reconstruct the attack timeline.
- Determine the likely infection vector.
- Identify patient zero and attack progression.

## Methodology

1. Verify dataset integrity.
2. Import logs into Splunk.
3. Filter suspicious security events.
4. Extract earliest suspicious activity per endpoint.
5. Correlate detections, quarantines, and network events.
6. Apply severity scoring and endpoint ranking.
7. Reconstruct the infection chain.
8. Determine the initial compromise vector.

## Skills Demonstrated

- Log Analysis
- Splunk
- Threat Hunting
- Event Correlation
- Timeline Reconstruction
- SIEM Operations
- Incident Investigation
- Digital Forensics
- Risk Assessment
- Technical Reporting

## Key Findings

- Multiple endpoints were identified as compromised.
- Event correlation enabled reconstruction of the infection sequence.
- Analysis identified the earliest compromised host.
- Evidence indicated malicious file execution as the initial attack vector.
- Subsequent activity suggested command-and-control communication attempts.

## Tools & Technologies

- Splunk Enterprise
- Endpoint Security Logs
- Web Activity Logs
- PowerShell
- CSV Data Sources

## Outcomes

- Reconstructed the attack timeline from available evidence.
- Identified likely patient zero and infection progression.
- Determined the probable compromise vector.
- Produced remediation recommendations and investigative findings.

## Repository Contents

- `Log_Analysis.pdf` – Full investigation report
- Supporting screenshots and analysis workflow

## Disclaimer

This case study is shared for educational and portfolio purposes. Any sensitive, proprietary, or assessment-specific information has been omitted or anonymized where appropriate.
