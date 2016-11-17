# Nancy

Nancy is a lightweight, low-ceremony, framework for building HTTP based services on .NET Framework/Core and [Mono](http://mono-project.com). The goal of the framework is to stay out of the way as much as possible and provide a super-duper-happy-path to all interactions.

Nancy is designed to handle `DELETE`, `GET`, `HEAD`, `OPTIONS`, `POST`, `PUT` and `PATCH` requests and provides a simple, elegant, [Domain Specific Language (DSL)](http://en.wikipedia.org/wiki/Domain-specific_language) for returning a response with just a couple of keystrokes, leaving you with more time to focus on the important bits..
**your** code and **your** application.

Write your application

```csharp
public class Module : NancyModule
{
    public Module()
    {
        Get("/greet/{name}", x => {
            return string.Concat("Hello ", x.name);
        });
    }
}
```

## The super-duper-happy-path

The "super-duper-happy-path" (or SDHP if you’re ‘down with the kids’ ;-)) is a phrase we coined to describe the ethos of Nancy; and providing the “super-duper-happy-path” experience is something we strive for in all of our APIs.

While it’s hard to pin down exactly what it is, it’s a very emotive term after all, but the basic ideas behind it are:

* “It just works” - you should be able to pick things up and use them without any mucking about. Added a new module? That’s automatically discovered for you. Brought in a new View Engine? All wired up and ready to go without you having to do anything else. Even if you add a new dependency to your module, by default we’ll locate that and inject it for you - no configuration required.
* “Easily customisable” - even though “it just works”, there shouldn’t be any barriers that get in the way of customisation should you want to work the way you want to work with the components that you want to use. Want to use another container? No problem! Want to tweak the way routes are selected? Go ahead! Through our bootstrapper approach all of these things should be a piece of cake.
* “Low ceremony” - the amount of “Nancy code” you should need in your application should be minimal. The important part of any Nancy application is your code - our code should get out of your way and let you get on with building awesome applications. As a testament to this it’s actually possible to fit a functional Nancy application into a single Tweet :-)
* “Low friction” - when building software with Nancy the APIs should help you get where you want to go, rather than getting in your way. Naming should be obvious, required configuration should be minimal, but power and extensibility should still be there when you need it.

Above all, creating an application with Nancy should be a pleasure, and hopefully fun! But without sacrificing the power or extensibility that you may need as your application grows.

## Project Details

- [Website](http://nancyfx.org/)
- [Source](https://github.com/NancyFx/Nancy)
- License: [MIT](https://github.com/dotnet/BenchmarkDotNet/blob/master/LICENSE.md)
- [NuGet](https://www.nuget.org/packages/Nancy)
- Project Lead: [Andreas Håkansson](https://github.com/thecodejunkie) & [Steven Robbins](https://github.com/grumpydev)

## Quicklinks

- [Documentation](https://github.com/NancyFx/Nancy/wiki/Documentation)
- [Slack](http://slack.nancyfx.org/)
- [Contributing](https://github.com/NancyFx/Nancy/blob/master/.github/CONTRIBUTING.md)
