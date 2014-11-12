# .NET Core 5

[.NET Core 5](http://github.com/microsoft/dotnet) is the small optimized runtime that is the basis of [ASP.NET Core 5](http://www.dotnetfoundation.org/aspnet-vnext). It currently runs on Windows, and will be extended to support Linux and Mac. It is a high-performance and modular design, and supports full side by side to make it easy to adopt new .NET Core versions without affecting other apps. These products are actively developed by the .NET team and in collaboration with a community of open source developers. Together we are dedicated to improving and extending the .NET platform with new features and for new scenarios.

.NET Core has two major components. It includes a small runtime that is built from the same codebase as the .NET Framework CLR. The .NET Core runtime includes the same GC and JIT (RyuJIT), but doesn’t include features like Application Domains or Code Access Security. The runtime is delivered on NuGet, via the Microsoft.CoreCLR package. 

.NET Core also include the base class libraries. These libraries are largely the same code as the .NET Framework class libraries, but have been factored (removal of dependencies) to enable us to ship a smaller set of libraries. These libraries are shipped as System.* NuGet packages on NuGet.org.

## Project Details

* [Project Info Site](https://github.com/Microsoft/dotnet)
* [Project Code Site](https://github.com/dotnet/corefx)
* Project License Type: [MIT](https://github.com/dotnet/corefx/blob/master/LICENSE)
* Project Main Contact: [Immo Landwerth](https://github.com/terrajobst)

## Quicklinks
* [Contribute](https://github.com/dotnet/corefx/blob/master/CONTRIBUTING.md)
* [Discussions](https://github.com/microsoft/dotnet/issues)
* [Blog](http://blogs.msdn.com/b/dotnet/)
* [Samples](https://github.com/Microsoft/dotnetsamples)
