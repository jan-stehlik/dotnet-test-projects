This is an example .NET app that has dependencies managed by `packages.config` and uses single target framework.

## Getting started

Prerequisites:

- [.NET](https://dotnet.microsoft.com/download) installed
- [Nuget CLI](https://docs.microsoft.com/en-us/nuget/install-nuget-client-tools#nugetexe-cli) installed

### Install dependencies

```bash
nuget install -OutputDirectory packages
```

### Build

```bash
dotnet build
```

### Run the app

Run for target framework net451

```bash
dotnet run
```
