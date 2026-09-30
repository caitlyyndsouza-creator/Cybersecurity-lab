Linux Security Monitoring and Authentication Analysis Lab

Project Overview
This project is a hands on cybersecurity lab designed to develop practical experience with Linux security monitoring, authentication analysis, log investigation and basic detection automation.
The lab was built in an isolated Ubuntu Linux virtual machine using VMware Fusion. Controlled authentication activity was generated and investigated to understand how Linux records security relevant events and how those events can be identified during an investigation.

Lab Environment
 Ubuntu Linux virtual machine
 VMware Fusion
 Linux command line
 Bash
 Git and GitHub

Tools & Technologies
 journalctl - reviewing system and authentication-related logs
 grep - filtering logs for security-relevant events
 Bash - automating log filtering and detection tasks
 Nano - creating and editing documentation and scripts
 Git - version control
 GitHub - project repository and documentation

Investigation Process
1. Baseline System Activity
Reviewed normal system activity to understand the expected behaviour of the Linux environment before generating test security events.

2. Authentication Testing
Generated controlled authentication activity within the lab environment including failed authentication attempts to observe how Linux records these events.

3. Log Analysis
Used journalctl to inspect system logs and investigate authentication and sudo activity.

Reviewed information including:
 Timestamps
 User activity
 Authentication results
 sudo events
 Processes associated with security events

4. Log Filtering
Used grep and command line filtering techniques to isolate security relevant events from larger system logs and make investigation more efficient.

5. Detection Automation
Created a Bash script to automate the filtering and identification of authentication-related events.
The script demonstrates how repetitive log analysis tasks can be automated rather than performed manually.

6. Documentation
Recorded investigation steps, observations and security findings in Markdown so that the analysis could be reproduced and reviewed.
Repository Structure

security-monitoring/
├── README.md
├── finding.md
└── scripts/

Skills Demonstrated
 Linux command-line administration
 Linux security monitoring
 Authentication log analysis
 sudo activity investigation
 Security event filtering
 Bash scripting
 Basic detection automation
 Security investigation documentation
 Git version control
 GitHub repository management

Key Learning Outcomes
This project demonstrated how Linux system logs can be used to investigate activity occurring on a host. It provided practical experience moving from raw log data to filtered security events, documenting findings and automating part of the detection process with Bash.
The project also established a structured workflow for security investigations:

Generate activity -> collect logs -> filter events -> investigate context -> document findings -> automate detection
