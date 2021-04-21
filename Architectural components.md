
----

## Architectural components

---

### NET Standard
Common set of API Specification that are present in all implementations of .NET.

for example there is function called `foo` that accepts 2 parameters.

API specification only tells there is function called `foo` that do some work. But it doesn't tell how it is doing its work.

Every implementation can implementation their own logic.

Note:- There will be no new .NET Standard versions after 2.1 as .NET 5 or later has combined everything into single SDK.

### .NET implementations
Each implementation of .NET includes the following components - 
- One or more runtimes --> .NET Framework CLR (Common Language Runtime), .NET 5 CLR.
- A class library --> .NET Framework BCL (Base class library), .NET 5 BCL.
- Optionally, one or more app frameworks. Examples: ASP.NET, Windows Forms, Windows Presentation Foundation (WPF) are included in the .NET Framework and .NET 5.
- Optionally, development tools. Some development tools are shared among multiple implementations.

There are 4 implementations of .NET that Microsoft supports :-

-  .NET 5 (and .NET Core) and later versions
-  .NET Framework
-  Mono
-  UWP

#### .NET 5
.NET 5 is now the primary implementation, the one that is the focus of ongoing development. .NET 5 is built on a single code base that supports multiple platforms and many workloads, such as Windows desktop apps and cross-platform console apps, cloud services, and websites.

#### .NET Framework
.NET Framework is the original .NET implementation and for windows only.

#### Mono
Mono is a .NET implementation that is mainly used when a small runtime is required. It is the runtime that powers Xamarin applications on Android, macOS, iOS, tvOS, and watchOS and is focused primarily on a small footprint. Mono also powers games built using the Unity engine.

#### UWP --> Universal Windows Platform
UWP is an implementation of .NET that is used for building modern, touch-enabled Windows applications and software for the Internet of Things (IoT). It's designed to unify the different types of devices that you may want to target, including PCs, tablets, phones, and even the Xbox. Apps can be written in C++, C#, Visual Basic, and JavaScript.

### .NET runtimes
A runtime is the execution environment for a managed code (code whose execution is managed by a runtime).

- **CLR** (Common Language Runtime) for .NET Framework
- **CLR** for .NET 5
- **.NET Native** for UWP
- The **Mono runtime** for Xamarin.iOS, Xamarin.Android, Xamarin.Mac, and the Mono desktop framework

