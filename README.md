# Docker Templates for Unraid

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
   https://raw.githubusercontent.com/YOUR-USERNAME/docker-templates/main/
   ```
   (Replace `YOUR-USERNAME` with your GitHub username)
5. Click "Save"

## Adding New Templates

1. Add your template XML file to the `templates/` directory
2. Update this README with the new template details
3. Commit and push your changes

## Repository Structure

- `templates/` - Contains all the template XML files
- `community.applications/` - Metadata for Unraid Community Applications
- `README.md` - This file

## License

MIT
