# NuGet Package: Escendit.Tools.SourceLink.Common
.NET NuGet package that simplifies the process of integrating [SourceLink](https://github.com/dotnet/sourcelink) into your project.
SourceLink provides a mechanism for debugging optimized code without sacrificing security by allowing you to use the actual source code for debugging, rather than decompiled code.

## Installation
To install `Escendit.Tools.SourceLink.Common`, you can use the NuGet Package Manager or run the following command in the Package Manager Console:

```shell
PM> Install-Package Escendit.Tools.SourceLink.Common
```
Or you can search for "Escendit.Tools.SourceLink.Common"
in the NuGet Package Manager UI and install it from there.

## Usage
Escendit.Tools.SourceLink.Common provides default common properties for SourceLink
that you can use in your .NET projects.
These default values are intended to simplify the process of integrating SourceLink into your project,
and can be overridden as needed.

This NuGet Package shouldn't be used directly, but is used as a dependency, and is currently used by:

- [Escendit.Tools.SourceLink.Embedded](https://github.com/escendit/Escendit.Tools.SourceLink.Embedded)
- [Escendit.Tools.SourceLink.GitLab](https://github.com/escendit/Escendit.Tools.SourceLink.GitLab)
- [Escendit.Tools.SourceLink.GitHub](https://github.com/escendit/Escendit.Tools.SourceLink.GitHub)

## Contributing
If you find a bug or have a feature request, please create an issue in the GitHub repository.

To contribute code, fork the repository and submit a pull request.
Please ensure that your code follows the project's coding standards and is thoroughly tested.

## License
This package is released under the MIT License. See the LICENSE.txt file for details.
