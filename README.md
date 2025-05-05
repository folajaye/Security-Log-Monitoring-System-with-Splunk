# Security-Log-Monitoring-System-with-Splunk
Real-time Windows log monitoring using Splunk.

## Objective
The project aims to enhance security monitoring capabilities by implementing Splunk to collect, analyze, and visualize Windows Event Viewer security logs.  This will enable real-time monitoring, threat detection, compliance reporting, and improve incident response.


## Tool used and its Objective
The tool used for this project is Splunk. This is a Security Information and Event Management tool, and it was used in this project for:
- Accepting Windows Event Viewer log files before processing their content for analysis.
- Visualizing key security events
- Continuous monitoring functions which was established through custom dashboard construction that ran alerts in real time.

## Tool Configuration
### Downloading Splunk:
- Visit the Splunk official website “https://www.splunk.com”
- Sign up/log in to download Splunk Enterprise (Free Trial for local machine)

### Installing Splunk:
- Run the installer for Windows
- Set admin username and password.
- Choose the default port (usually 8000).
- Start Splunk and access via http://localhost:8000.

### Enabling Windows Event Log Input:
- Navigate to Settings > Data Inputs
- Add new input for Local Event Logs.
- Add applications, Security, and System as selected log channels and save.

### Clearing Event Viewer Security Logs
Open Event Viewer:
- Press the Windows button, search Event Viewer, and hit Enter.
- Navigate to Windows Logs > Security.

Clearing Logs:
- Right-click Security and select Clear Log.
- Confirm the action to clear all events.

## Key findings
The successful installation and configuration of Splunk allows the system to consume Windows Event Viewer log information. Security logs were received to establish proper monitoring parameters. A specific security dashboard presented important security events for preventive threat management.

## Recommendations
### Immediate Remediation Actions
- The configuration of Splunk should be optimized to retrieve all security-related log data.
- Regular monitoring of the Splunk dashboard should be carried out to identify any suspicious security events.
- Set up Splunk for real-time scenario monitoring by enabling alerts for vital security events, including forceful attacks.

### Long-Term Mitigation
- Integrate Splunk with other security tools and other devices to ingest logs for comprehensive security monitoring.
- User Behavior Analytics: Identify unusual login behavior.
- Schedule weekly reviews of Splunk dashboards for anomalies.
- Security Awareness: Train users to report login anomalies.


[Full Report on Medium](https://medium.com/@folajayeabdulrahman/building-a-security-log-monitoring-system-with-splunk-a-technical-walkthrough-0eda9454b8af)















