# Shares

When you run Windows 10 or 11 and want to access a network share using guest credentials (no login) you will need to make a few changes in your local GPO's (Group Policy Objects) and local registry.  

## Group Policy Objects

1. Run `gpedit` 
2. Go to `Computer Configuration\Administrative Templates\Network\Lanman Workstation`
3. Edit `Enable insecure guest logons`
4. Choose `Enabled` and click OK.

## Registry

In `HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\LanmanWorkstation\Parameters` you should create a `DWORD (32-bit) Value` named `AllowInsecureGuestAuth` and set the value data to `1`.