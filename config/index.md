---
_layout: landing
---

# DynamoForRevitUtils Framework

**DynamoForRevitUtils** is a comprehensive C# framework designed to extend and enhance Dynamo for Revit functionality, 
providing powerful utilities for building information modeling (BIM) workflows and automation.

## Key Features

### 🔧 Core Utilities & Services
- **Revit Services**: Comprehensive services for interacting with Revit elements, parameters, and document management
- **Collectors**: Specialized collection services for walls, rooms, phases, and other Revit elements
- **Units Conversion**: Built-in unit conversion utilities for seamless measurement handling
- **Math Services**: Advanced mathematical operations tailored for BIM workflows

### 📊 Data Management
- **CSV Operations**: Read and write CSV files with dedicated node models for data import/export
- **Excel Integration**: Handle Excel files for data exchange and reporting
- **File Services**: Comprehensive file management utilities
- **Collections Management**: Advanced collection handling and manipulation services

### 🎯 Element Selection & Filtering
- **Selection Services**: Interactive element selection with customizable filters
- **Pick Selection Filters**: Advanced filtering capabilities for precise element selection
- **Selection Results Management**: Structured handling of selection operations

### 📐 Geometry & Visualization
- **Abstract Geometry Viewer**: Advanced geometric operations and calculations
- **Topography Services**: Specialized tools for handling topographic elements

### 🏗️ BIM-Specific Features
- **Wall Elevation**: Specialized tools for wall analysis and elevation management
- **Section Creation**: Automated section view creation with customizable parameters
- **Axis Management**: Tools for handling structural axes and grids
- **Room & Space Analysis**: Comprehensive room and space management utilities
- **MEP Curve References**: Utilities for mechanical, electrical, and plumbing systems

### 🔄 Parameter Management
- **Parameter Handlers**: Advanced parameter manipulation and management
- **Built-in to UI Name Conversion**: Convert internal Revit names to user-friendly display names
- **Parameter Type Detection**: Automatic parameter type identification and handling
- **Access Parameter Modes**: Multiple modes for parameter access and modification

### 📋 Node Models & Functions (Documentation on nodes)
- **Custom Node Models**: Pre-built node models for common BIM operations
- **Dropdown Functions**: Interactive dropdown controls for parameter selection
- **Text Functions**: Advanced text manipulation and processing
- **Default Inputs**: Predefined input values for common scenarios

### 🔍 Advanced Capabilities
- **Reflection Services**: Dynamic type inspection and manipulation
- **Enumeration Utilities**: Comprehensive enumeration handling and conversion
- **Tag Information Management**: Advanced tagging and annotation services
- **Join Lines Services**: Geometric line joining and manipulation

## Framework Architecture

The framework is organized into several key namespaces:

- **`DynamoForRevitUtils.Services`**: Core service classes
- **`DynamoForRevitUtils.Entities`**: Data models and entity classes
- **`DynamoForRevitUtils.Enumerations`**: Framework-specific enumerations
- **`DynamoForRevitNodeModels`**: Custom Dynamo node implementations
- **`NodeModelsFunctions`**: Function-based node implementations

## Getting Started

To use DynamoForRevitUtils in your Dynamo ZeroTouch nodes project, you have two options:

1. Download package from [Nuget.org](https://www.nuget.org/). Search for `DynamoForRevitUtils` and download the package.


2. Install Nuget package directly on your project using the following command:

```text
dotnet add package DynamoForRevit.<RevitVersionNumber>.ZeroTouchUtils --version <package version>
```

> **Note:** Revit version number could be: 2022, 2023, 2024, 2025.


> **Note:** See below a list of supported Revit and Dynamo versions.
> 
> Revit 2022.1 ➡️ Dynamo 2.12
> 
> Revit 2023.1 ➡️ Dynamo 2.16
> 
> Revit 2024.2 ➡️ Dynamo 2.19
> 
> Revit 2025.4 ➡️ Dynamo 3.3

## Integration with Dynamo

The framework seamlessly integrates with Dynamo for Revit, providing:

- Custom node models that appear in the Dynamo library
- Enhanced parameter management capabilities
- Advanced geometry processing tools
- Streamlined BIM workflow automation

## Documentation

This documentation provides comprehensive API reference for all classes, methods, and properties available in 
the DynamoForRevitUtils framework. Navigate through the API sections to explore the full capabilities of each component.

---

*DynamoForRevitUtils - Enhancing BIM workflows through intelligent automation.*