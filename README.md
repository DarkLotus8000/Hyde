# hyde
<ins>**hyde.dll**</ins> hides a process from the Task Manager on Windows 2000 - Windows 10 (x86/x64 Bit).

Your process can inject it into other processes however you like. The example uses SetWindowsHookEx with a CBT hook (the dll exports a CBTProc) to inject it into all running processes.

Press Esc to exit the script.

Note: if you do not compile the script, AutoHotKey.exe gets hidden. Otherwise the the name of the .exe gets hidden.

**Important:** This does only work if you are using a x64 Bit OS and the 64-Bit version of AutoHotkey or if you're using a x86 (32-Bit) OS and the 32-Bit version of AutoHotkey. This does not work if you have a x64 bit OS but use 32-Bit AHK (and vice versa)!
