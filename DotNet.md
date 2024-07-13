# .NET & .NET Core Command List

This document provides a complete list of commands used in .NET and .NET Core.

## Table of Contents

- [.NET Core CLI Commands](#net-core-cli-commands)
- [.NET Framework Commands](#net-framework-commands)

## .NET Core CLI Commands

| Command                                          | Description                                             |
|--------------------------------------------------|---------------------------------------------------------|
| `dotnet new <template>`                          | Create a new project or file of the specified template. |
| `dotnet build`                                   | Build the project and its dependencies.                |
| `dotnet run`                                     | Run the application.                                   |
| `dotnet test`                                    | Run unit tests using the test runner.                  |
| `dotnet publish`                                 | Publish the application and its dependencies to a folder. |
| `dotnet restore`                                 | Restore dependencies specified in the project file.    |
| `dotnet add package <package-name>`             | Add a NuGet package reference to the project.          |
| `dotnet remove package <package-name>`          | Remove a NuGet package reference from the project.     |
| `dotnet list package`                            | List the packages referenced by the project.           |
| `dotnet clean`                                   | Clean the output of the previous build.                |
| `dotnet migrate`                                 | Migrate a project to a new format.                     |
| `dotnet publish -c <configuration>`             | Publish the application with a specific configuration (e.g., Debug, Release). |
| `dotnet ef migrations add <MigrationName>`      | Create a new migration for Entity Framework.           |
| `dotnet ef database update`                      | Update the database to the latest migration.           |
| `dotnet ef database drop`                        | Drop the database for the current context.             |
| `dotnet ef migrations list`                      | List all migrations for the current context.           |

## .NET Framework Commands

| Command                                          | Description                                             |
|--------------------------------------------------|---------------------------------------------------------|
| `msbuild <project-file>`                         | Build the project using MSBuild.                       |
| `devenv <solution-file>`                         | Open the solution in Visual Studio.                    |
| `nuget install <package-name>`                  | Install a NuGet package.                               |
| `nuget update <solution-file>`                   | Update NuGet packages in a solution.                  |
| `msbuild /t:Rebuild`                             | Clean and rebuild the project.                         |
| `sn -k <key-file>`                               | Create a new strong name key file.                     |
| `gacutil -i <assembly>`                          | Install an assembly into the Global Assembly Cache.    |
| `xcopy <source> <destination> /E /I`            | Copy files and directories, including subdirectories.  |

