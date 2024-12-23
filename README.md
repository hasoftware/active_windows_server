# active_windows_server

1. Windows Server 2022 Datacenter    
   Bật Windows PowerShell với quyền Administrator và sau đó dán dòng lệnh dưới đây vào:
```bash
DISM /online /Set-Edition:ServerDatacenter   /ProductKey:WX4NM-KYWYW-QJJR4-XV3QB-6VM33 /AcceptEula
```

2. Windows Server 2022 Standard  

 Bật Windows PowerShell với quyền Administrator và sau đó dán dòng lệnh dưới đây vào:
```bash
DISM /online /Set-Edition:ServerStandard   /ProductKey:VDYBN-27WPP-V4HQT-9VMD4-VMK7H /AcceptEula
```

3. Windows Server 2019 Datacenter  
 Bật Windows PowerShell với quyền Administrator và sau đó dán dòng lệnh dưới đây vào:
```bash
DISM /online /Set-Edition:ServerDatacenter   /ProductKey:WMDGN-G9PQG-XVVXX-R3X43-63DFG /AcceptEula
```

4. Windows Server 2019 Standard  
 Bật Windows PowerShell với quyền Administrator và sau đó dán dòng lệnh dưới đây vào:
```bash
DISM /online /Set-Edition:ServerStandard   /ProductKey:N69G4-B89J2-4G8F4-WWYCC-J464C /AcceptEula
```

5. Windows Server 2016 Datacenter  
 Bật Windows PowerShell với quyền Administrator và sau đó dán dòng lệnh dưới đây vào:
```bash
DISM /online /Set-Edition:ServerDatacenter   /ProductKey:CB7KF-BWN84-R7R2Y-793K2-8XDDG /AcceptEula
```

6. Windows Server 2016 Standard  
 Bật Windows PowerShell với quyền Administrator và sau đó dán dòng lệnh dưới đây vào:
```bash
DISM /online /Set-Edition:ServerStandard   /ProductKey:WC2BQ-8NRM3-FDDYY-2BFGV-KHKQY /AcceptEula
```

7. Windows Server 2012 R2 Datacenter  
 Bật Windows PowerShell với quyền Administrator và sau đó dán dòng lệnh dưới đây vào:
```bash
DISM /online /Set-Edition:ServerDatacenter   /ProductKey:W3GGN-FT8W3-Y4M27-J84CP-Q3VJ9 /AcceptEula
```

8. Windows Server 2012 R2 Standard  
 Bật Windows PowerShell với quyền Administrator và sau đó dán dòng lệnh dưới đây vào:
```bash
DISM /online /Set-Edition:ServerStandard   /ProductKey:D2N9P-3P6X9-2R39C-7RTCD-MDVJX /AcceptEula
```

9. Windows Server 2012 Datacenter  
 Bật Windows PowerShell với quyền Administrator và sau đó dán dòng lệnh dưới đây vào:
```bash
DISM /online /Set-Edition:ServerDatacenter   /ProductKey:48HP8-DN98B-MYWDG-T2DCC-8W83P /AcceptEula
```

10. Windows Server 2012 Standard  
 Bật Windows PowerShell với quyền Administrator và sau đó dán dòng lệnh dưới đây vào:
```bash
DISM /online /Set-Edition:ServerStandard   /ProductKey:XC9B7-NBPP2-83J2H-RHMBY-92BT4 /AcceptEula
```

11. Windows Server 2008 R2 Datacenter  
 Bật Windows PowerShell với quyền Administrator và sau đó dán dòng lệnh dưới đây vào:
```bash
DISM /online /Set-Edition:ServerDatacenter   /ProductKey:74YFP-3QFB3-KQT8W-PMXWJ-7M648 /AcceptEula
```

12. Windows Server 2008 R2 Standard  
 Bật Windows PowerShell với quyền Administrator và sau đó dán dòng lệnh dưới đây vào:
```bash
DISM /online /Set-Edition:ServerStandard   /ProductKey:YC6KT-GKW9T-YTKYR-T4X34-R7VHC /AcceptEula
```

13. Windows Server 2008 R2 Enterprise  
 Bật Windows PowerShell với quyền Administrator và sau đó dán dòng lệnh dưới đây vào:
```bash
DISM /online /Set-Edition:ServerEnterprise   /ProductKey:489J6-VHDMP-X63PK-3K798-CPX3Y /AcceptEula
```

14. Windows Server 2008 Datacenter  
 Bật Windows PowerShell với quyền Administrator và sau đó dán dòng lệnh dưới đây vào:
```bash
DISM /online /Set-Edition:ServerDatacenter   /ProductKey:7M67G-PC374-GR742-YH8V4-TCBY3 /AcceptEula
```

15. Windows Server 2008 Standard  
 Bật Windows PowerShell với quyền Administrator và sau đó dán dòng lệnh dưới đây vào:
```bash
DISM /online /Set-Edition:ServerStandard   /ProductKey:TM24T-X9RMF-VWXK6-X8JC9-BFGM2 /AcceptEula
```

16. Windows Server 2008 Enterprise  

 Bật Windows PowerShell với quyền Administrator và sau đó dán dòng lệnh dưới đây vào:
```bash
DISM /online /Set-Edition:ServerEnterprise   /ProductKey:YQGMW-MPWTJ-34KDK-48M3W-X4Q6V /AcceptEula
```


CUỐI CÙNG CHẠY LỆNH DƯỚI ĐÂY ĐỂ KÍCH HOẠT MÁY CHỦ 
```bash
slmgr /skms kms.digiboy.ir
```

```bash
slmgr /ato
```
