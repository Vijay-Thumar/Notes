If you are using **Windows CMD or PowerShell**, Git auto-completion does not work by default. Instead, install **Posh-Git** for PowerShell:

#### **For PowerShell**

1. Open **PowerShell as Administrator**.
    
2. Run the following command:
    
    powershell
    
    CopyEdit
    
    `Install-Module posh-git -Scope CurrentUser`
    
3. Add the following line to your PowerShell profile (`$PROFILE`):
    
    powershell
    
    CopyEdit
    
    `Add-PoshGitToProfile -AllHosts`
    
4. Restart PowerShell.