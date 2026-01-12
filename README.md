<h1>Digital Forensics - Archive File Analysis</h1>

<h2>Description</h2>
Forensic investigation of a suspicious compressed archive file requiring secure extraction, content analysis, and metadata examination. This project demonstrates proper evidence handling, file enumeration, and data recovery using an isolated virtual environment to prevent potential system compromise.
<br />

<h2>Investigation Objectives</h2>

- Enumerate all files within the archive
- Recover sensitive/hidden data
- Identify file creator (user attribution)
- Establish file creation timeline (UTC)

<h2>Tools and Utilities Used</h2>

- <b>Windows 11 Virtual Machine (VirtualBox)</b>
- <b>File Explorer</b> - Archive extraction and file enumeration
- <b>Notepad</b> - File content examination
- <b>Windows File Properties</b> - Metadata analysis

<h2>Environments Used</h2>

- <b>Windows 11</b> (Isolated VM environment)
- <b>VirtualBox</b> - Virtualization platform for secure analysis

<h2>Investigation Walk-through:</h2>

<p align="center">
Extract the suspicious archive file in isolated environment: <br/>
<img src="https://imgur.com/a/vAXDPwO" height="80%" width="80%" alt="Archive Analysis Steps"/>
<br />
<br />
Enumerate files within the extracted "secrets" directory:  <br/>
<img src="https://imgur.com/YCZArKj" height="80%" width="80%" alt="Archive Analysis Steps"/>
<br />
<br />
Review "note" file for additional intelligence:  <br/>
<img src="https://i.imgur.com/XXXXXXX4.png" height="80%" width="80%" alt="Archive Analysis Steps"/>
<br />
<br />
</p>

<h2>Key Findings</h2>

- <b>Files in Archive:</b> 2 files identified (flag, note)
- <b>Sensitive Data Recovered:</b> SKY-LRDA-9420
- <b>File Creator:</b> [Identified via metadata analysis]
- <b>Creation Timestamp:</b> [UTC timestamp from file properties]

<h2>Skills Demonstrated</h2>

- Digital forensics and file analysis
- Secure isolated environment configuration
- Evidence preservation and systematic enumeration
- Data recovery from compressed archives
- File content examination and documentation

<h2>Real-World SOC Applications</h2>

This investigation workflow directly applies to:
- <b>Phishing Response:</b> Analyzing suspicious email attachments safely
- <b>Malware Triage:</b> Safe extraction and examination of potentially malicious archives
- <b>Incident Response:</b> Evidence collection and data recovery from compromised systems
- <b>Threat Hunting:</b> Identifying hidden or obfuscated files in compressed archives
- <b>Digital Forensics:</b> Maintaining chain of custody during file analysis
