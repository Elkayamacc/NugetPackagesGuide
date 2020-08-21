# NugetPackagesGuide
`This guide made for people that already knows how to pack nuget but dont know how to target dlls by Configuration.`</br>
For example : I have 4 different versions of DLLS (x64 release, x64 debug, x86 release , x86 debug)  and i want to compile a code with a package, instead of creating 4 different nuget packages i can automaticly target in compilation the one i need and to create only 1 pack of nuget (if i want to compile in x86 debug the compiler will target the x86 debug DLL).

## Prerequisites ##

-Download Nuget.exe and put it also in this directory.</br>
-Put all the files in the same Directory of your project directory (Example: if the project directory is "D://Myproject" put all the files(Nuget.exe, nuspec, props and targets in "D://")</br>
-Make sure the name of all the files (Nuspec, Props, Targets) is the same name 

