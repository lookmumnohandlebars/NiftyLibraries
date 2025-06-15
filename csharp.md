# Nifty Libraries for C#

> A curated list of libraries that supercharge development for C#/.NET. These libraries have been vetted to meet a high standard and have been personally used before recommending. There tends to be only one library per use-case (i.e. I've mostly opted for a favorite of two, rather than including every library)
> You can choose to this as a starter-list for "accepted" open-source libraries for your company, department or project, and expand as you need (preventing duplication of problems that have already been solved.

Table Of Contents:
[Utility](#Utility)

## Utility

> Libraries that can apply to almost any type of code!

### 🧰 Types

> Types that can extend or improve your use of the language (and write cleaner code!)

- [**LanguageExt** (Functional Utilities)](https://github.com/louthy/language-ext): Simply put... any application can have this included almost by default. Includes a bunch of extra basic types
- [**FluentResults** (Specialized result type)](https://github.com/altmann/FluentResults): 
- [**ErrorOr** (Error-Result type)](https://github.com/amantinband/error-or): Like the Option or Result type, but with an "error-handling first" approach.

<details>
  <summary> System Library Bits To Not Forget!</summary>

  - 
</details>

### 💪 Resiliency

- [**Polly** (Resiliency/Retries)](https://github.com/App-vNext/Polly):
- [**Microsoft.Extensions.Resilience**]:

### ☑️ Validation & Sanitization
- [**FluentValidation** (Validation)](https://github.com/FluentValidation/FluentValidation):
- [**DataAnnotations** (Validation)](https://learn.microsoft.com/en-us/dotnet/api/system.componentmodel.dataannotations?view=net-9.0): Including this also as for most simple cases, it should be enough, but lacks the customization that FluentValidation has
- [**Throw** (Guard Clauses)](https://github.com/amantinband/throw):
- [**HtmlSanitizer**](https://github.com/mganss/HtmlSanitizer): If you need a large amount of control over sanitizing

### Networking

- RestSharp:

### Background Tasks

- 

### 💽 Data Handling
- [**System.Text.Json** (JSON)](https://www.nuget.org/packages/system.text.json/): Microsoft's in-house json library is now the standard, and it comes with some tricky-to-learn but easy-to-use paradigms, especially when it comes to customization.
- [**CsvHelper** (CSV))](https://github.com/JoshClose/CsvHelper): Much easier than doing parsing using anything the System library has.
- [**YamlDotNet** (YAML)](https://github.com/aaubry/YamlDotNet): 
- [**Tomlyn** (TOML)](https://github.com/xoofx/Tomlyn): Excellent TOML handling... slightly too much string key indexing for my liking, so use with caution, but still cool.
- [**dotenv.Net** (.env)](https://github.com/bolorundurowb/dotenv.net):


### 🎏 Asynchrony, Concurrency and Multithreading

> These are advanced libraries for managing asynchrony (tasks) beyond the System.Tasks library.

- [**Channels**]():
- [**Dataflow**]():
- [**Reactive**]():
- [**Linq Async**]():

### 💉 Dependency Injection

- [**Microsoft.DependencyInjection**](): While others exist are widely used, I would highly recommend sticking to using the native
- [**Scrutor**](https://github.com/khellang/Scrutor): This library neatly wraps around the microsoft DI library to add lovely things like decoration.


---

## Application / Frameworks

## 💾 CLI / Console

> These libraries are for developing 

- [**Cocona** (CLI Framework)](https://github.com/mayuki/Cocona): Makes composing a high-quality 
- [**Spectre.Console** (Console API)]():
- [**Kurukuru** (Spinner)]():
- [**Dumpify** (Table-Printing)]():

## 🫵 Interactive (REPL's, Playgrounds & Notebooks)
- [**Dotnet Interactive** (Generic Background Library)](https://github.com/dotnet/interactive)
- [**Dotnet Script** (Scripting in C#)]()
- [**Polyglot Notebooks** (Jupyter Notebooks)]

## 🕸 Web (Back-End)
- 

## 🖼 Web (Front-End)
- 

## 📜 API Documentation
- [**Microsoft.OpenAPI** (OpenAPI)](https://github.com/Microsoft/OpenAPI.NET): Where swagger once ruled, Microsoft's OpenAPI.NET is now the best of all worlds! Highly recommended!
- [**Kiota** (SDK Generation)](https://github.com/microsoft/kiota): Not specifically .NET... but you can use really neatly with OpenAPI to generate SDK's, and save yourself HOURS of development.
- [**DocFX** (Document Site Generation)](https://github.com/dotnet/docfx): The .NET team's own take on developer docs, integrates really well with both XML docs and standard .NET repos! You can also generate


## ䷓ Templating
- [**RazorEngineCore** (Templated Strings)](https://github.com/adoconnection/RazorEngineCore)
- []

## 🔐 Security

> For obvious reasons, the dotnet/microsoft libraries have the most security. However there are some specialist cases

- [**JWT**]():
- [**NSec** (Cryptography)](https://github.com/ektrah/nsec): A trusted utility library

## Wonderful But Things I Don't Use Regularly
