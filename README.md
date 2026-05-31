# SA.XTB.CompareSecurityRoles

An XrmToolBox plugin for comparing Dataverse security roles across two environments.

## Overview

This tool helps you:

- Connect to two Dataverse environments
- Load root business unit security roles
- Compare security role privileges between environments
- Highlight matching, missing, extra, and mismatched privileges
- Filter results by entity name
- Hide matched rows if desired
- Export comparison results to CSV

## Features

- **Two-environment comparison** for security roles and privileges
- **Async data loading** so long-running operations do not freeze the UI
- **Root business unit role filtering**
- **Privilege parsing** into entity name and privilege action
- **Color-coded results grid** for easy review
- **Entity filtering** and option to hide matched rows
- **CSV export** for reporting and analysis
- **XrmToolBox integration** with small and large tool images

## Requirements

- XrmToolBox
- Dataverse / Dynamics 365 access
- .NET Framework 4.8.1

## Installation

### Via NuGet

Install the package into XrmToolBox or your plugin distribution workflow using the NuGet package:

`SA.XTB.CompareSecurityRoles`

### Manual

1. Copy the plugin DLL into the XrmToolBox plugins folder
2. Ensure the required dependencies are available
3. Start XrmToolBox and load the plugin

## Usage

1. Open the tool in XrmToolBox
2. Connect the first environment
3. Connect the second environment
4. Select a source role and a target role
5. Review the comparison grid
6. Use the filter box or the hide-matched option as needed
7. Export results to CSV when required

## Package Information

- **Package ID:** `SA.XTB.CompareSecurityRoles`
- **Target Framework:** `net481`
- **Tool Type:** XrmToolBox plugin

## Support

If you find an issue or want a feature added, please open an issue in the project repository.
