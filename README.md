# CLRHostPlugin
###Obsolete, used as dependency for CLRBrowserSourcePlugin

Updated for Visual Studio 2013
Removed DirectX SDK requirement, now uses Windows SDK DirectX

##Build:
All project folders must be located in the same parent folder, usually Documents.

Get OBS source code, not OBS-studio. Requires DirectX SDK.

Extract to folder, make sure its named 'OBS'.

Open OBS-all.sln, set release/debug x64/x86, build solution.

Open CLRHostPlugin folder, open the .sln file.

Make sure the project has the same release/debug x64/x86 settings as OBS did. CLRHostPlugin depends upon a library built in OBS.

Build Solution.

You are now prepared to build CLRBrowserSourcePlugin.




