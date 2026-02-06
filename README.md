Some quick Powershell scripts

DLL_Check_s is a simple DLL checker, made to for DLLs loaded from user-writable locations using Event ID 7 from Sysmon logs

DLL_Check_f is a more full version, it will read the DLL Hijack events from the specified log file and filters them based on the current working directory (CWD). It checks if the CWD is in a user-writable location such as AppData
## Temp, ProgramData, or Public. If a match is found, it outputs the relevant information including the time of the event, the image path, command line, current directory, and user.

Nothing Crazy
