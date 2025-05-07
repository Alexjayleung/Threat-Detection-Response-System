<h1>Threat Detection and Response System</h1>

<h2>Description</h2>

This project is a simulation of a real-world enterprise-grade Network Threat Detection & Response System, designed to detect suspicious activity, collect system logs, and respond to potential security threats in real time. The system pulls logs from both Windows and Linux machines, analyzes them for suspicious behavior using custom detection logic, and can trigger automated responses such as alerts or system isolation.

A key feature of this project is the inclusion of a visual dashboard, which provides a centralized interface to view threat alerts, system activity, and detection results. This dashboard helps visualize patterns, track incidents, and simulate how a Security Operations Center (SOC) would monitor and react to threats in a live network.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Python</b> – for log parsing, detection logic, and alerting
- <b>PowerShell</b> – for monitoring and automated response on Windows systems
- <b>Sysmon (Sysinternals)</b> – collects detailed system activity logs on Windows
- <b>rsyslog</b> – forwards logs from Linux systems
- <b>Regex</b> – used in detection logic for identifying suspicious patterns
- <b>Flask</b> – to build a lightweight web-based dashboard
- <b>YARA (optional)</b> – rule-based scanning for malware detection




<h2>Environments Used </h2>

- <b>Windows 10/11 VM</b> – for testing Sysmon logging and PowerShell response scripts
- <b>Ubuntu Linux VM</b> – for rsyslog testing and log forwarding
- <b>Kali Linux</b> – to simulate attacks and generate threat scenarios
- <b>VirtualBox</b> – used to host all virtual machines in an isolated lab environment
- <b>Linux Terminal & Windows Command Prompt</b> – for manual log inspection and running scripts
- <b>Elasticsearch & Kibana (optional)</b> – for enterprise-grade log indexing and visualization



<h2>Lab Overview:</h2>
<br />
