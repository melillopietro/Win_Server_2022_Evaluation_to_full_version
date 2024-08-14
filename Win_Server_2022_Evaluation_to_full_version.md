# Windows Server 2022 Evaluation (Eval) to Full Version

## Download Windows Server 2022 Evaluation English from Microsoft
* https://software-static.download.prss.microsoft.com/sg/download/888969d5-f34g-4e03-ac9d-1f9786c66749/SERVER_EVAL_x64FRE_en-us.iso

## Upgrade (Eval) to Full version
- Open cmd (run as administrator), then use
### Upgrade to STANDARD
```cmd
dism /online /set-edition:serverstandard /productkey:VDYBN-27WPP-V4HQT-9VMD4-VMK7H /accepteula
```

### Upgrade to DATACENTER
```cmd
dism /online /set-edition:serverdatacenter /productkey:WX4NM-KYWYW-QJJR4-XV3QB-6VM33 /accepteula
```