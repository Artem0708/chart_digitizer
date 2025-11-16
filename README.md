# Chart Digitizer 🎯

An interactive web-based tool for digitizing charts and converting graphical data into numerical CSV format. Perfect for extracting data from images of graphs, charts, and plots.

![Chart Digitizer](https://img.shields.io/badge/Chart-Digitizer-blue)
![HTML5](https://img.shields.io/badge/HTML5-Compatible-green)
![CSV Export](https://img.shields.io/badge/Export-CSV-brightgreen)

## Features ✨

- **🖱️ Interactive Point Placement**: Click to add data points directly on the canvas
- **⏰ Time-Based Restrictions**: Enforce one point per time period (month, week, day, etc.)
- **📊 Multiple Export Options**:
  - **Original Points**: Export only the exact points you placed
  - **Smoothed Curve**: Generate 200 interpolated points for smooth curves
  - **Combined**: Both original and interpolated points
- **🎯 Smart Point Management**:
  - Right-click to delete points
  - Visual feedback for occupied time slots
  - Automatic grid snapping
- **⚙️ Customizable Settings**:
  - Adjustable time range (start/end)
  - Custom cost/value ranges
  - Multiple period types (months, weeks, days, quarters, years)

## Quick Start 🚀

1. **Download** the `digitizer.html` file
2. **Open** it in any modern web browser (Chrome, Firefox, Safari, Edge)
3. **Configure** your time and cost ranges
4. **Click** "Apply Settings"
5. **Add points** by clicking on the canvas
6. **Process data** and download CSV

## Usage Guide 📖

### Setting Up Your Chart

1. **Time Range**: Set the start and end values for your X-axis
2. **Cost Range**: Define the minimum and maximum values for your Y-axis
3. **Period Type**: Choose the time unit (months, weeks, days, etc.)

### Adding Data Points

- **Left-click** on the canvas to add a point
- Points automatically snap to the nearest time unit
- Only one point allowed per time period
- **Right-click** near a point to delete it

### Export Options

- **Original Points**: Use when you want exactly the data points you placed
- **Smoothed Curve**: Creates a smooth curve with 200 interpolated points
- **Both**: Combines original points with additional interpolated points

## Example Use Cases 📊

- **Business**: Digitize revenue growth charts
- **Research**: Extract data from scientific plots
- **Finance**: Convert stock market charts to numerical data
- **Academia**: Analyze historical data from published graphs

## CSV Output Format 📄

The tool generates CSV files with two columns:

```csv
time,cost
0.00,0.00
1.00,15000.00
2.00,30000.00
...
