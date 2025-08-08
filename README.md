# dcit318-assignment2-11125009

This repository contains three C# console applications demonstrating core OOP concepts:

1. Inheritance and Method Overriding (`InheritanceOverrideApp`)
2. Abstract Classes and Methods (`AbstractShapesApp`)
3. Interfaces (`InterfacesMovableApp`)

## Prerequisites
Install the .NET SDK: https://aka.ms/dotnet/download

Verify installation:

```bash
dotnet --version
```

## How to run
From the repository root, run each app:

```bash
# Inheritance and Method Overriding
cd InheritanceOverrideApp
 dotnet new console -n InheritanceOverrideApp # if project not yet restored
 dotnet run

# Abstract Classes and Methods
cd ../AbstractShapesApp
 dotnet run

# Interfaces
cd ../InterfacesMovableApp
 dotnet run
```

Note: Projects are already scaffolded in this repo. If you cloned a fresh copy and the `*.csproj` files exist, `dotnet run` will restore and run.

## Commit history
- Commit 1: Inheritance and Method Overriding
- Commit 2: Abstract Classes and Methods
- Commit 3: Interfaces 