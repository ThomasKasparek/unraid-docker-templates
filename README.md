# Docker Templates for Unraid

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This repository contains Docker templates for easy deployment on Unraid servers. These templates are designed to work with Unraid's Community Applications plugin.

## Available Templates

- **Compiler Explorer** - Interactive compiler for C++, Rust, Go, and more
  - Port: 10240
  - Data Path: `/mnt/user/appdata/compiler-explorer`

## Adding This Repository to Unraid

1. In your Unraid web interface, go to the "Apps" tab
2. Click the puzzle piece icon in the top-right corner
3. Select "Template Repositories" tab
4. Add this URL:
   ```
   https://raw.githubusercontent.com/ThomasKasparek/docker-templates/main/
   ```
5. Click "Save"

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
