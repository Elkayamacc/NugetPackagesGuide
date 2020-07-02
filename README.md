# NugetPackagesGuide
`This guide is for people whom already knows how to pack nuget but doesnt know how to target dlls.`</br>
for example : i have 4 different versions of package(x64 release, x64 debug, x86 release , x86 debug)  and i want to compile a code with a package, instead of creating 4 different nuget packages i can automaticly target in compilation the one i need (if i want to compile in x86 debug , the vs automaticly will do it).

## Prerequisite ##

-Download Nuget.exe and put it also in this directory.</br>
-Put all the files in the same Directory of your project directory (Example: if the project directory is D://Myproject put all the files(Nuget.exe, nuspec, props, targets in D://)

