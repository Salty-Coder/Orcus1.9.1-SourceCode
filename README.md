# Orcus 1.9.1 Source Code 
# Credits snyke

# This repository doesn't contain my code. I have uploaded it to GitHub for those want to analyse the code.
I'm not associated with the development and production of this program are not responsible for any actions and or damages caused by this software. You bear the full responsibility of your actions and acknowledge that this software was created for educational purposes only. This software's intended purpose is NOT to be used maliciously, or on any system that you do not have own or have explicit permission to operate and use this program on. By using this software, you automatically agree to the above.

https://cracked.to/Thread-Leak-C-Orcus-1-9-1-RAT-Full-Source-Code-Leaked

C# RAT with lots of features.


## Build
- Open `Orcus.sln` in Visual Studio
- Set the build option to `Release`
- Press Ctrl + Shift + B to build the complete solution (do this until it does nothing if you build)
- Set the build option back to `Debug`
- Press Ctrl+ Shift + B again
- At first, start `Orcus.Server.bin.Debug` > `Orcus.Server.exe` . Here, you have to enter an ip address and a port. Remember it! (127.0.0.1:10134 is recommended for tests)
- Last, start `Orcus.Administration.Bin.Release` > `Orcus.Administration.exe` and connect to the server (again with the ip/port)

## Issue Resolving
If you are asked for a license key then do the following:
- Open `Orcus.Administration` > `OrcusActivator.cs` in a text editor
- Replace all the code with the contents of `UsefulFiles` > `OrcusActivator.cs`
- Rebuild the project
- In `Orcus.Administration.Bin.Release`, create an empty file and name it `license.orcus`
