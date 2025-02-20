# appsvolume

Open the windows volume mixer app from the taskbar and start menu.

How to use

1. Create a shortcut of the batch file.
2. Right-click on the `.link` file and select **Properties**.
3. In the **Target** field, add `cmd.exe /c` before the path to the batch file, `cmd.exe /c "C:\foo\bar\appsvolume\appsvolume.bat"` (don't forget to add `""`).
4. Click **Apply**.
5. Right-click on the shortcut file again and select **Pin to taskbar** (you might need to select **Show more options** in Windows 11).
