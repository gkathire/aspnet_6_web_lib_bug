**Problem Description**
When I include a Web Sdk Class library( which has Sdk="Microsoft.NET.Sdk.Web") in a Console app which of type Microsoft.NET.Sdk (which uses the TargetFramework : net5.0), the .net 6 preview compiler does not compile and throws the following error:

`C:\Program Files\dotnet\sdk\6.0.100-preview.6.21355.2\Microsoft.Common.CurrentVersion.targets(4969,5): error MSB3030: Could not copy the file "C:\WebLibraryFail\lib\obj\Debug\net5.0\staticwebassets\WebLibraryFail.WebLib.StaticWebAssets.xml" because it was not found. [C:\WebLibraryFail\WebLibraryFail.csproj]

The build failed. Fix the build errors and run again.`

When I compile the same solution in VS 2019, it works perfectly.