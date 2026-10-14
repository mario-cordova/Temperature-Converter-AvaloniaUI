# Temperature Converter

A cross-platform desktop application built with [Avalonia UI](https://avaloniaui.net/) that converts temperatures from degrees Celsius (°C) to degrees Fahrenheit (°F). It is based on the [Avalonia starter tutorial](https://docs.avaloniaui.net/docs/get-started/starter-tutorial), where the default template is turned into a temperature converter.

<img width="1920" height="1080" alt="Captura de pantalla_20261014_002550" src="https://github.com/user-attachments/assets/c49d5405-7fc6-4699-857f-5c14b94f83ea" />


## Features

- One-click conversion from °C to °F.
- UI built with Avalonia controls and layout containers.
- Logic in code-behind through a button event handler.
- Cross-platform: Windows, macOS, and Linux.

## Requirements

- [.NET SDK](https://dotnet.microsoft.com/download) (10.0+)
- Optional: an IDE with Avalonia support, such as Visual Studio, JetBrains Rider, or VS Code

## How to run it

1. Clone the repository:

   ```bash
   git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git
   cd YOUR_REPO
   ```

2. Restore dependencies and run:

   ```bash
   dotnet run
   ```

## How to use it

1. Enter a temperature in degrees Celsius.
2. Click the convert button.
3. The result in degrees Fahrenheit appears on screen.

The conversion uses this formula:

```
°F = °C × 9/5 + 32
```

## Project structure

```
.
├── App.axaml                 # Application definition and global styles
├── Program.cs                # Entry point
├── Views/
│   ├── MainWindow.axaml      # Main window UI (Avalonia XAML)
│   └── MainWindow.axaml.cs   # Code-behind: button event and conversion logic
└── *.csproj                  # Project configuration and NuGet packages
```

> Folder and file names may vary depending on the template you used to create the project.

## What you learn from this project

This project walks through the basic concepts of Avalonia:

- Adding a control (a button) to the window.
- Arranging multiple controls with layout containers.
- Customizing the window: size, title, and other attributes.
- Responding to events, such as a button click.
- Converting data from code-behind.

## Technologies

- [Avalonia UI](https://avaloniaui.net/)
- C# and .NET
- AXAML (Avalonia XAML)

## Resources

- [Avalonia documentation](https://docs.avaloniaui.net/)
- [Starter tutorial: temperature converter](https://docs.avaloniaui.net/docs/get-started/starter-tutorial)
