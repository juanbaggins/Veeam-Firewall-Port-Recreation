# Veeam-Firewall-Port-Recreation
<b>Description:</b> Scripts used to recreate the default Veeam inbound and outbound firewall ports that are created during installation of Veeam Backup and Recovery.<br>
<b>Why:</b> Veeam support does not have this information apparently. And is not willing to create a script for this purpose.<br>
<b>Examples:</b>
```Powershell
Set-ExecutionPolicy -ExecutionPolicy Remotesigned -Scope Process -Force; .\Recreate-VeeamOutboundFirewallRules.ps1
Set-ExecutionPolicy -ExecutionPolicy Remotesigned -Scope Process -Force; .\Recreate-VeeamInboundFirewallRules.ps1
