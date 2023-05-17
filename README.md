## NOTE: ShellAPI is in beta and has not been fully finished; if you have any problems, please report them in the issues tab



## Requirements:
1: Lua v5.3 minimum runtime added to your path environment variables

2: Windows 10 / 11

3: Access to the command prompt

## Instructions:
1: Download the .zip file

2: Move it to your user profile (How to get there? Windows Key + R and type %USERPROFILE%)

3: Unzip the contents

4: Drag the folder and shortcut out of the folder so it's in your user profile's  directory

5: Run the shortcut to finish initialization

## Patch Notes: v2.0-PTB

```ini
[+] Added Bootstrapper
[+] ShellAPI now has its own standalone executable launcher
[+] Command Utility Development and -home commands are now part of the shells session %PATH% variable when launching from the executable

[-] Removed test folder in CUD workspaces
[-] Removed ShellAPI folder in CUD workspaces
[-] Removed beta resources left over from development

[*] Crashing when using -ep (patched with .syn and .synf files)
```
## To-Do List: v3.0-PTB

```ini
[+] Quick Patcher app
[+] Launch configurator and configuration files
[+] Lua runtime built in and added to %PATH&
```
