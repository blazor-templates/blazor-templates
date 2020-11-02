# blazor-templates

[![Nuget](https://img.shields.io/nuget/v/BlazorTemplates)](https://www.nuget.org/packages/BlazorTemplates/)
[![Nuget](https://img.shields.io/nuget/dt/BlazorTemplates)](https://www.nuget.org/packages/BlazorTemplates/)
[![License](https://img.shields.io/github/license/blazor-templates/blazor-templates)](https://github.com/blazor-templates/blazor-templates)

A collection of project templates for blazor

The goal of this project is to maintain a set of project templates that get rid of the main challenges with new blazor projects (e.g. when one wants to use material design, one first needs to edit&remove a lot of files, before the project is properly set up).

# Installation

Add the templates to your machine by running

```
dotnet new -i BlazorTemplates
```

# Usage

## 1. Pick template

Browse the templates (`dotnet new` to see them all), to find the name of the template you want to install, e.g. `blazor-vanilla-wasm`.

## 2. Create new project

```bash
mkdir my_project
cd my_project
dotnet new blazor-vanilla-wasm
# or
dotnet new blazor-vanilla-wasm --name MyProjectName
```

# Source code for templates

The source code for the templates can be found in the [templates](https://github.com/blazor-templates/blazor-templates/tree/main/templates) folder.
