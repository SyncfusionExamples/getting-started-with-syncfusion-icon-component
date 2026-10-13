# Getting Started with Syncfusion Icon Component in Blazor WebAssembly

## Overview

This sample demonstrates how to use the Syncfusion Blazor Icon component in a hosted Blazor WebAssembly application. The project showcases rendering built-in Syncfusion icons, configuring icon sizes, customizing icon appearance, and displaying tooltips for better user interaction and accessibility. It serves as a practical reference for developers who want to incorporate consistent iconography into their Blazor applications while leveraging the built-in icon support provided by Syncfusion components. The sample is structured as a hosted Blazor WebAssembly solution with separate Client, Server, and Shared projects.

## Key Features

- Render built-in Syncfusion icons using the `SfIcon` component and predefined `IconName` values such as `Cut`, `Copy`, and `Paste`.
- Display icon tooltips by using the `Title` property to provide descriptive text for icons.
- Customize icon appearance through the `@attributes` directive and dynamically pass HTML attributes such as inline styles using a `Dictionary<string, object>`.
- Apply custom colors and visual styling to individual icons without affecting other icon instances.
- Render external or custom icon libraries through the `IconCss` property of the `SfIcon` component.
- Demonstrate integration with Open Iconic icons using custom CSS class values.
- Display icons within Syncfusion buttons using the `SfButton` component and the `IconCss` property.
- Configure button icon placement using the `IconPosition` property.
- Render icons directly through CSS classes using the standard `e-icons` icon font implementation.
- Illustrate multiple icon rendering approaches, including Syncfusion predefined icons, custom CSS-based icons, button icons, and standalone icon font elements.

## Prerequisites

- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or [Visual Studio Code](https://code.visualstudio.com/)
- [.NET SDK](https://dotnet.microsoft.com/en-us/download/dotnet) compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download this repository.
2. Open `GettingStarted.sln`.
3. Restore all NuGet packages.
4. Build the solution.
5. Press `Ctrl+F5` to run the application.

**Visual Studio Code**

1. Open the repository folder in Visual Studio Code.
2. Open a terminal in the repository root directory.
3. Restore the required NuGet packages:

```bash
dotnet restore
```

4. Run the application:

```bash
dotnet run
```

5. Open the local application URL displayed in the terminal after the application starts.

## Project Structure

`Client/Pages/Index.razor` - Demonstrates Syncfusion `SfIcon` usage with predefined `IconName` values, tooltip support through the `Title` property, custom styling using `@attributes`, custom icon rendering through `IconCss`, integration with `SfButton`, and direct CSS-based icon rendering.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- Official documentation: https://blazor.syncfusion.com/documentation/appearance/icons

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.