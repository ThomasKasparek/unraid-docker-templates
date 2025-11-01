# Unraid Docker Templates

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This repository contains Docker templates for easy deployment on Unraid servers. These templates are designed to work with Unraid's Community Applications plugin.

## Available Templates

- **Compiler Explorer** - Interactive compiler for C++, Rust, Go, and more
  - Port: 10240
  - Data Path: `/mnt/user/appdata/compiler-explorer`

## Adding This Repository to Unraid 7.2

1. In your Unraid web interface, go to the "Apps" tab
2. Click the "Apps" dropdown in the top-right corner
3. Select "Appdata Backup / Restore v2" (install it from Community Apps if you don't have it)
4. In the Appdata Backup settings, add a new "Custom Template Source":
   ```
   https://raw.githubusercontent.com/ThomasKasparek/unraid-docker-templates/main/
   ```
5. Click "Apply" and wait for the templates to download

Alternatively, you can manually download the template:

1. Download the template file: [compiler-explorer.xml](https://raw.githubusercontent.com/ThomasKasparek/unraid-docker-templates/main/templates/compiler-explorer.xml)
2. In Unraid, go to the "Docker" tab
3. Click "Add Container"
4. Click "Template" at the top and select "Import"
5. Upload the downloaded XML file

## Adding New Templates

1. Add your template XML file to the `templates/` directory
2. Update this README with the new template details
3. Commit and push your changes

## Repository Structure

- `templates/` - Contains all the template XML files
- `community.applications/` - Metadata for Unraid Community Applications
- `README.md` - This file

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
