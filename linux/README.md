# Linux Security Rules Collection

This folder contains security detection rules for Linux systems collected from multiple sources, all in one directory.

## Sources & File Naming
- **elastic-\*.toml**: Rules from elastic/detection-rules (rules/linux)  
- **sigma-\*.yml**: Rules from SigmaHQ/sigma (rules/linux)
  - **sigma-auditd-\*.yml**: Auditd-specific rules
  - **sigma-builtin-\*.yml**: Builtin log rules
  - **sigma-file_event-\*.yml**: File event rules
  - **sigma-network_connection-\*.yml**: Network connection rules
  - **sigma-process_creation-\*.yml**: Process creation rules

## Statistics
- Elastic Linux rules: 309
- Sigma Linux rules: 206
- **Total rule files: 515**

## Rule Categories (from SigmaHQ)
The Sigma Linux rules are organized by log source type:
- **auditd**: Linux audit daemon rules[2]
- **builtin**: Built-in Linux system log rules
- **file_event**: File system monitoring rules
- **network_connection**: Network activity detection rules
- **process_creation**: Process execution monitoring rules

Last updated: 2025-09-23 16:31:42 UTC
