# Updates?!
This repo is older builds and mostly unmaintained in favor of:
 - Native builds (AMD64 + AARCH64): https://github.com/sec/dotnet-core-freebsd-source-build
 - Crossbuilds (AMD64): https://github.com/Thefrank/dotnet-freebsd-crossbuild
 - Source builds: Soon(TM)

# dotnet-freebsd-native-binaries
Native built, via bootstrap, dotnet under FreeBSD

## Why should I use this?
 - It is crossgen'd (https://github.com/dotnet/runtime/blob/main/docs/workflow/building/coreclr/crossgen.md)
   - The native build with azure pipelines is a flex
   - This is the public output of a private build

## What is here?
 - Generally, The FreeBSD-x64 (AMD64) SDKs for 3.1, 5.0, 6.0, 7.0.
 - Newish: 6.0, 7.0. EOL: 3.1 and 5.0

## What's Used?
- Bootstrap and NuGet files crossbuilt under Linux from: https://github.com/Thefrank/dotnet-freebsd-crossbuild
- Scripts from: https://github.com/sec/dotnet-core-freebsd-source-build
- Azure build logic from: https://github.com/Servarr/dotnet-bsd/
- Working Azure Pipelines Agent: https://github.com/Thefrank/azure-pipelines-agent-freebsd

## How do I use this?
- See here: https://github.com/Thefrank/dotnet-freebsd-crossbuild
