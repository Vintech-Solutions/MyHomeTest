1. Please note when you have a loop with install just continue once all is done created a Project shortcut.
2. Once shortcut is on desktop
3. Go To control Panel and Uninstall the Project
4. Once Uninstall is complete just test the shortcut link
5. Done Test 

regsvr32 "C:\Program Files (x86)\Project\editlistview2.ocx"

For the Dos Error!!!

You will need to Map  \\10.10.1.34\Project\Reports on the client PC with ebh\ebhdc and the password : tP4R@W!!tP4R@W!!



Start-Process msiexec -ArgumentList "/i \\fileserver01\SysAdmin\Project\Project.msi /quiet /norestart" -Verb RunAs
