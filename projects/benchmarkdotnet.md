# BenchmarkDotNet

**BenchmarkDotNet** is a powerful .NET library for benchmarking.

**Summary**

* Standard benchmarking routine: generating an isolated project per each benchmark method; auto-selection of iteration amount; warmup; overhead evaluation; statistics calculation; and so on.
* Supported runtimes: Full .NET Framework, .NET Core (RTM), Mono
* Supported languages: C#, F#, and Visual Basic
* Supported OS: Windows, Linux, MacOS
* Easy way to compare different environments (`x86` vs `x64`, `LegacyJit` vs `RyuJit`, and so on; see: [Jobs](http://benchmarkdotnet.org/Configs/Jobs.htm))
* Reports: markdown, csv, html, plain text, png plots.
* Advanced features: [Baseline](http://benchmarkdotnet.org/Advanced/Baseline.htm), [Params](http://benchmarkdotnet.org/Advanced/Params.htm)
* Powerful diagnostics based on ETW events (see [BenchmarkDotNet.Diagnostics.Windows](https://www.nuget.org/packages/BenchmarkDotNet.Diagnostics.Windows/))

## Project Details

- [Website](http://benchmarkdotnet.org/)
- [Source](https://github.com/dotnet/BenchmarkDotNet)
- License: [MIT](https://github.com/dotnet/BenchmarkDotNet/blob/master/LICENSE.md)
- [NuGet](https://www.nuget.org/packages/BenchmarkDotNet/)
- Project Lead: [Andrey Akinshin](https://github.com/AndreyAkinshin)

## Quicklinks

- [Documentation](http://benchmarkdotnet.org/)
- [Overview](http://benchmarkdotnet.org/Overview.htm)
- [Gitter](https://gitter.im/dotnet/BenchmarkDotNet)
- [ChangeLog](https://github.com/dotnet/BenchmarkDotNet/wiki/ChangeLog)