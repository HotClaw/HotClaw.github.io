## Megabytes
```bash
"{0} MB" -f ((Get-ChildItem * -Recurse | Measure-Object -Property Length -Sum -ErrorAction Stop).Sum / 1MB)
```

## Bytes
```bash
Get-ChildItem * | Measure-Object -Property Length -sum
```
