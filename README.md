# TSSv2Cluster
Uses TSSv2 to run one command we use in support


# TSSv2Cluster

Automation tool for MS NEtworking 

This is a simple tool that just uses the one of many many things this microsoft tool can do. 

![tssv2 tool](https://learn.microsoft.com/en-us/troubleshoot/windows-client/windows-troubleshooters/introduction-to-troubleshootingscript-toolset-tssv2)


The focus We use is likely to be the list of SDP reports. I have listed them here for my team mates. 


![image](https://user-images.githubusercontent.com/79279019/201212440-f94d509f-74e6-4cdb-bfbc-8904cf376b7d.png)


  How To Use: 
 Use the URL Below. Put into a powershell window and the files will download into the Downloads Folder. They will unzip and TSSv2Cluster will begin. You will 
 see the menu in the above screen shot.  
```Powershell
[Net.ServicePointManager]::SecurityProtocol = [Net.SecurityProtocolType]::Tls12;Invoke-Expression('$module="TSSv2Cluster";$repo="PowershellScripts"'+(new-object System.net.webclient).DownloadString('https://raw.githubusercontent.com/Louisjreeves/TSSv2Cluster/main/TSSv2.ps1')); Invoke-TSSv2Cluster
```
