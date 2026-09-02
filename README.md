[![](https://img.shields.io/nuget/v/soenneker.clamav.freshclam.windows.svg?style=for-the-badge)](https://www.nuget.org/packages/soenneker.clamav.freshclam.windows/)
[![](https://img.shields.io/github/actions/workflow/status/soenneker/soenneker.clamav.freshclam.windows/build-and-test.yml?style=for-the-badge)](https://github.com/soenneker/soenneker.clamav.freshclam.windows/actions/workflows/build-and-test.yml)
[![](https://img.shields.io/nuget/dt/soenneker.clamav.freshclam.windows.svg?style=for-the-badge)](https://www.nuget.org/packages/soenneker.clamav.freshclam.windows/)
[![](https://img.shields.io/github/actions/workflow/status/soenneker/soenneker.clamav.freshclam.windows/codeql.yml?style=for-the-badge)](https://github.com/soenneker/soenneker.clamav.freshclam.windows/actions/workflows/codeql.yml)

# Soenneker.Clamav.Freshclam.Windows

The official ClamAV FreshClam runtime packaged for Windows x64 .NET applications.

## Installation

```powershell
dotnet add package Soenneker.Clamav.Freshclam.Windows
```

The package copies its runtime beneath `Resources/win-x64/freshclam/`. Most applications should reference `Soenneker.Clamav.Freshclam.Util`, which selects the platform and provides the managed update API.

## Licensing and source

The package scaffolding is MIT-licensed. The bundled ClamAV runtime is GPL-2.0-only and preserves its upstream `COPYING.txt`, third-party notices, and exact release provenance in `SOURCE.txt`.
