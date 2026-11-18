# Sysmon Process Investigation
### Objective
Analyze process creation events using Sysmon and understand the information recorded during process execution.
### Environment
- Windows 11
- Sysmon
- Windows Event Viewer
### Investigation
Launched Windows Calculator using PowerShell and reviewed Sysmon Event ID 1 (Process Create).
### Findings
- Process: CalculatorApp.exe
- Event ID: 1
- Process ID: 8300
- Parent Process: sihost.exe
- Parent PID: 408
- Integrity Level: AppContainer
- Timestamp (UTC): 2026-11-18 10:23:44.883

Sysmon successfully recorded the Calculator process creation event.

### Conclusion
This lab provided hands-on experience with Windows process monitoring and identifying parent-child process relationships using Sysmon.
