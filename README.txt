This is the same thing as Git-Cheetah, except this only has the "Git Branch" context menu in explorer.

1. Build the solution or use one of the dll's in these locations:
	explorer\visualstudio\Win32\Release\git_shell_ext.dll
	explorer\visualstudio\x64\Release\git_shell_ext64.dll

2. Copy the dll to your preferred location, eg:
	C:\Program Files (x86)\Git-Cheetah-GitBranchOnly

3. CMD or Powershell to that folder and run one of these, depending on which file you copied:
	regsvr32.exe .\git_shell_ext64.dll
	regsvr32.exe .\git_shell_ext.dll

4. "Git Branch" should now be available in your explorer context menu.

For further details, see the original Git Cheetah on github.
https://github.com/msysgit/Git-Cheetah

