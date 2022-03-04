## Windows10-Activation

## Run Cmd as admin then copy this, (No Internet)  

```bash
dism /Online /Get-TargetEditions
```
```bash
sc config LicenseManager start= auto & net start LicenseManager
```
```bash
sc config wuauserv start= auto & net start wuauserv
```
```bash
changepk.exe /productkey VK7JG-NPHTM-C97JM-9MPGT-3V66T
```

## Pro-Activation (With Internet)

```bash
slmgr.vbs /ipk W269N-WFGWX-YVC9B-4J6C9-T83GX
```
```bash
slmgr.vbs /skms kms.teevee.asia 
```
```bash
slmgr.vbs /ato 
```
