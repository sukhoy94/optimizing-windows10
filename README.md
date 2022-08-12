# optimizing-windows10

# remove diagtrack

```
sc delete DiagTrack
sc delete dmwappushservice
echo "" > C:\ProgramData\Microsoft\Diagnosis\ETLLogs\Autologger\AutoLogger-diagtrack-Listener.etl
```
