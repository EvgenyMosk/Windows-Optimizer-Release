# Windows-Optimizer-Release
Windows Optimizer Releases

version 0.1.0 [Alpha]
Changes the following values in registry:
1. HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Session Manager\Memory Management
    "DisablePagingExecutive" to "1"   (Default value: "0")
2. HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Session Manager\Memory Management
    "LargeSystemCache"       to "1"   (Default value: "0")
3. HKEY_CURRENT_USER/Control Panel/Desktop
    "MenuShowDelay"          to "0"   (Default value: "400")
