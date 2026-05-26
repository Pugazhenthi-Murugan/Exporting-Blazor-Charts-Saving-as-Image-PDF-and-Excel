# Blazor Chart Export

Export interactive [Blazor Charts](https://www.syncfusion.com/blazor-components/blazor-charts) in multiple formats - PNG, PDF, and Excel - directly from your Blazor web application.

## Overview

This project demonstrates how to build a robust chart exporting solution in Blazor using .NET 8. Visualize data with beautiful interactive charts and effortlessly export them in the formats your users need. Perfect for reports, presentations, and data analysis workflows.

## Features

- **Multiple Export Formats** - Export charts as PNG images, PDF documents, or Excel spreadsheets
- **Interactive Charts** - Rich, responsive data visualization with tooltips and animations
- **Real-time Export** - Seamless, user-friendly export experience with event handling
- **Production Ready** - Built with best practices for scalability and maintainability
- **Modern Stack** - Leverages .NET 8 and the latest Blazor Server components

## Prerequisites

- [.NET SDK 8.0](https://dotnet.microsoft.com/download/dotnet/8.0) or later
- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or later
- [Visual Studio Code](https://code.visualstudio.com/)

## Getting Started

### Clone the repository

```bash
git clone https://github.com/SyncfusionExamples/AI-Powered-Predictive-Analysis-for-Stock-Trends-in-Syncfusion-Blazor-Chart.git
cd AI-Powered-Predictive-Analysis-for-Stock-Trends-in-Syncfusion-Blazor-Chart
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

## Usage

### Exporting Charts

The application provides three export options accessible via simple button clicks:

- **Export as Image** - Download chart as PNG format
- **Export as PDF** - Generate landscape-oriented PDF report
- **Export as Excel** - Export chart data to XLSX spreadsheet

Each export type is optimized for its respective format:

- **PNG**   - Presentations & Web 
- **PDF**   - Reports & Documents 
- **Excel** - Data Analysis 

## Export Customization

The chart export functionality can be customized by modifying:

- **Export filename** - Change the filename parameter in export calls
- **PDF orientation** - Toggle between landscape and portrait modes
- **Chart styling** - Customize colors, fonts, and layout before export
- **Data source** - Modify the chart data collection for different datasets

## References
- Chart Export Documentation: https://blazor.syncfusion.com/documentation/chart/chart-print
- Blazor Chart Export Demo: https://blazor.syncfusion.com/demos/chart/export/