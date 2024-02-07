# Batch Utils
A multipurpose collection of batch scripts for Windows devices

## Available Scripts

| Scripts | Details | Downloads |
| --- | --- | --- |
| rammap scheduler | Script to automate the creation of RAMMap scheduled tasks | [rammap-scheduler.bat][rammap-scheduler] |
| chrome version | Get the installed Google Chrome version number | [chrome-version.bat][chrome-version] |


## Notes

 - **RAMMap Scheduler**: You need to download RAMMap from [here][rammap] and edit the EXE_PATH variable in this script in order to use this script.

Example:
```sh
SET EXE_PATH=C://RAMMap/RAMMap.exe
```

 - **Chrome Version**
This script will search for any installed version of Google Chrome and retrieve the version number. This can be useful for development and testing purposes.


[rammap-scheduler]: scripts/rammap-scheduler.bat

[chrome-version]: scripts/chrome-version.bat

[rammap]: https://live.sysinternals.com/RAMMap.exe
