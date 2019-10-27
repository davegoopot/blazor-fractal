# Learning Blazor - Fractal Display

## Introduction

In order to learn Blazor, this project is to write a program to draw fractals in a browser.
Specifically the [Mandelbrot set](https://en.wikipedia.org/wiki/Mandelbrot_set).

## Getting Started

Tutorial introduction: https://docs.microsoft.com/en-us/aspnet/core/blazor/

### Hello World!

See https://github.com/davegoopot/blazor-fractal/issues/1

#### Install the Required Components

See https://docs.microsoft.com/en-us/aspnet/core/blazor/get-started

1. Install the .NET core 3.1 SDK version. Ignore the docs that say the .NET core 3.0 version will work. Download it from here: https://dotnet.microsoft.com/download/dotnet-core/3.1 
1.  
1. Make sure the .NET core 3.1 SDK is installed

        dotnet  --list-sdks
            3.1.100-preview1-014459 [C:\Program Files\dotnet\sdk]
1. I'm working in Visual Studio code, so check have the latest C# extension installed
1. Install the Blazor templates

        dotnet new -i Microsoft.AspNetCore.Blazor.Templates::3.1.0-preview1.19508.20

1. Add the Blazor WebAssembly experience

        dotnet new blazorwasm -o WebApplication1

1. Add the Blazor Server experience

        dotnet new blazorserver -o WebApplication1

1. Change to the web application folder and build it

        cd .\WebApplication1\
        dotnet run

1. Check that the application is running on: https://localhost:5001



