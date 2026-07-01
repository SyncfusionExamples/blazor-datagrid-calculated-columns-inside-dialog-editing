# Blazor DataGrid - Calculated Columns with Dialog Editing

A sample Blazor application demonstrating how to automatically update calculated columns in the [Blazor DataGrid](https://www.syncfusion.com/blazor-components/blazor-datagrid) component when editing values through a dialog interface.

## Overview

This repository demonstrates how to implement reactive calculated columns in a Blazor DataGrid component. When users edit price and quantity values through a dialog, the total amount is automatically recalculated and updated without requiring manual computation or page refresh.

## Features

- **Real-time Calculations**: Automatic total computation based on price and quantity inputs
- **Dialog-Based Editing**: Edit form with inline number inputs for a polished user experience
- **Reactive Components**: Uses Blazor event bindings to trigger instant updates
- **Validation**: Built-in validation rules for required fields
- **Formatting**: Currency formatting (C2) for financial data display

## Prerequisites

* [.NET SDK 10.0](https://dotnet.microsoft.com/en-us/download/dotnet/10.0) or later
* [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or later
* [Visual Studio Code](https://code.visualstudio.com/)

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/SyncfusionExamples/blazor-datagrid-calculated-columns-inside-dialog-editing.git
cd blazor-datagrid-calculated-columns-inside-dialog-editing
```

### Run with Visual Studio

1. Open the solution file using Visual Studio 2022 or later.
2. Restore the NuGet packages by rebuilding the solution.
3. Build the project to ensure there are no compilation errors.
4. Run the project.

### Run with .NET CLI

```bash
# Restore dependencies
dotnet restore

# Run the project
dotnet run
```

## References

**Documentation**: https://blazor.syncfusion.com/documentation/datagrid/in-line-editing

**Online example**: https://blazor.syncfusion.com/demos/datagrid/inline-editing?theme=fluent2