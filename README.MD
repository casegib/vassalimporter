# Vassal Importer

A Foundry Virtual Tabletop module for importing Vassal modules into Foundry VTT.

## Description

Vassal Importer enables Game Masters and players to convert and import game modules from Vassal into Foundry VTT, facilitating the migration of existing Vassal-based campaigns and content.

## Features

- Import Vassal module files into Foundry VTT
- Convert Vassal game data and assets
- Intuitive user interface for managing imports
- Progress tracking during import operations

## Installation

1. In Foundry VTT, navigate to **Add-on Modules**
2. Click **Install Module**
3. Paste the manifest URL into the Manifest URL field:
   ```
   https://raw.githubusercontent.com/casegib/vassalimporter/main/module.json
   ```
4. Click **Install**
5. Enable the module in your world

## Usage

1. Open the Vassal Importer dialog from the module interface
2. Select your Vassal module file (.vmod or equivalent)
3. Configure import settings as needed
4. Click **Import** and monitor the progress
5. Your Vassal content will be converted and added to your Foundry VTT world

## Compatibility

- **Minimum Foundry Version**: 10
- **Verified on Version**: 13

## Requirements

This module uses the following libraries:
- jszip - for handling compressed Vassal module files
- FileSaver - for file export functionality

## Development

### Project Structure

```
vassalimporter/
├── module.json                 # Module manifest
├── styles/
│   └── vassal-importer.css    # Module styling
├── modules/
│   ├── vassal-importer.js     # Main module script
│   └── vassal-importer-api.js # API definitions
└── lib/                        # External libraries
    ├── jszip/
    ├── jszip-utils/
    └── FileSaver.min.js
```

### Building

[Add build instructions if applicable]

## Support

For issues, feature requests, or bug reports, please open an issue on the project repository.

## Author

- **CaseGib**

## License

[Add license information]

## Changelog

### v0.0.1
- Initial release
