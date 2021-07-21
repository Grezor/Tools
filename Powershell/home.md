```powershell
echo $PROFILE
C:\Users\Geoffrey\Documents\WindowsPowerShell\Microsoft.PowerShell_profile.ps1
```

```powershell
Import-Module posh-git
Import-Module oh-my-posh
# Set-PoshPrompt -Theme jandedobbeleer
Set-PoshPrompt -Theme hotstick.minimal

if (!(Test-Path -Path $PROFILE)) { New-Item -ItemType File -Path ROFILE -Force }
```

