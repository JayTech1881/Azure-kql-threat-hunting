# Azure-kql-threat-hunting
## Objective
Demonstrate how to use Kusto Query Language (KQL) in Azure Log Analytics to identify and investigate potential security threats.

## Lab Activities
• Queried Azure Log Analytics workspace using KQL
• Identified suspicious IP activity in log data
• Extracted the IP address for further investigation
• Analyzed the IP using VirusTotal threat intelligence

## Findings
A suspicious external IP address appeared in log activity.

VirusTotal analysis returned 1 detection from a security vendor, indicating potential malicious activity.

## Security Analysis
While a single detection does not confirm malicious intent, the IP was flagged as suspicious and would require further monitoring and investigation in a real SOC environment.

## Lessons Learned
• KQL is a powerful tool for threat hunting
• Threat intelligence platforms help validate suspicious indicators
• SOC analysts must correlate log data with external intelligence sources
