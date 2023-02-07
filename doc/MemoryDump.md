# Memory Dump
## Get the Outline of the Issue
```
!analyze -v
```
- First of all, you need to run this command to know the outline of the issue.
## Get the Computer Name
```
!ustr srv!srvcomputername
```
## Get the Debug Session Time
```
vertarget
```
## Get Event Logs
```
!wmitrace.eventlogdump 0x09
```