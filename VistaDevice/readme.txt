To compile the audio-device.cpp

1. You should have already installed or copied MSSDK.
2. Create a shortcut like: C:\WINDOWS\system32\cmd.exe /E:ON /V:ON /T:0E /K "E:\VimProject\MSSDK\Bin\SetEnv.Cmd /xp"
3. Click the shortcut to start console and then in the console, run "gvim makefile"
4. When VIM started, run :set makeprg=nmake.exe
5. run :make to make this cpp.
6. exe file will be produced in the XP32_DEBUG, change the shortcut parameter for VISTA 32/64 DEBUG/RELEASE version. View the file MSSDK\Bin\SetEnv.Cmd 
7. Since this exe is invoking VISTA API, start vmware to test the exe.


The output lib files for this project VimProject\VistaDevice: audio-device.h $OUTPUt/audio-device.dll $OUTPUt/audio-device.lib 

