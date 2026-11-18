Sysmon Process Investigation

Objective

Analyze process creation events using Sysmon and understand the information recorded during process execution.

Environment

* Windows 11
* Sysmon
* Windows Event Viewer

Investigation

Launched Windows Calculator and checked the Sysmon Operational log for Event ID 1 (Process Creation).

Reviewed the event details to identify the process information and execution time.

Findings

* Event ID: 1
* Process: Windows Calculator
* Process ID: 25584
* Timestamp: 2026-11-17 13:22:16.852

Sysmon successfully recorded the process creation event.

Conclusion

This lab provided hands-on experience with Windows process monitoring and basic endpoint investigation using Sysmon.
