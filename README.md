# Windows-Optimizer-Release
Windows Optimizer Releases

# Requirements
1. Microsoft .NET Framework 3.5
2. Administrator Privileges

# Release Notes

# version 0.2.0, build 2019.10.19 [Alpha] 
1. All registry paths, keys and values are now stored in external XML file.
    If you need to edit more values - just edit the XML file.
2. Now, the Administrator Privilages will be asked automaticaly, so you don't need to launch the application with Adm. Priv.                                                         manually. 

# version 0.1.0 [Alpha]
Changes the following values in registry:
1. HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Session Manager\Memory Management
    "DisablePagingExecutive" to "1"   (Default value: "0")
2. HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Session Manager\Memory Management
    "LargeSystemCache"       to "1"   (Default value: "0")
3. HKEY_CURRENT_USER/Control Panel/Desktop
    "MenuShowDelay"          to "0"   (Default value: "400")
