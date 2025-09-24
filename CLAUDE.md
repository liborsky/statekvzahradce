# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This repository contains a Czech accommodation website project "Statek v Zahrádce" (Farm in Zahrádka) - a rural guesthouse and event venue located near Orlík Dam. The project consists of static HTML files for a website presentation.

## Project Structure

### Main Content
- `index.html` - Large Wix-generated HTML file (759KB) containing the main website content exported from a Wix website
- `index_files/` - Supporting assets for the main HTML file
- `final/index.html` - Clean, hand-coded responsive website version in Czech

### Additional Content
- `StatekVZahradce/` - Directory containing:
  - `statek_prezentace.html` - Custom presentation page for the accommodation
  - `foto/` - Image gallery with property photos (DSC00214.jpg, DSC00340.jpg, statek.jpg, stodola1.jpg)
  - `fotkystatek.zip` - Archive containing additional property photos
- Various backup files (.backup extensions)

## Website Content

The website showcases a rural accommodation facility with:
- **Accommodation**: 6 rooms for up to 14 guests
- **Event Space**: Barn capacity for 50 seated guests
- **Amenities**: Swimming pool (4x8m), sauna, private garden (1,600m²)
- **Services**: Weddings, events, group accommodation
- **Location**: Zahrádka village, 3km from Orlík Dam

## Development Notes

### Technology Stack
- **Frontend**: Static HTML with embedded CSS and JavaScript
- **Original Source**: Wix website (exported/saved content)
- **Custom Version**: Hand-coded responsive HTML in `final/` directory

### File Characteristics
- Large HTML files due to Wix export format with inline styles and extensive JavaScript
- Czech language content throughout
- Responsive design implementation in custom version
- Image assets stored in dedicated photo directories

### Working with Content
- Main Wix file (`index.html`) is very large - use `limit` parameter when reading
- Custom presentation page (`StatekVZahradce/statek_prezentace.html`) is more manageable for editing
- Image files are high-resolution photos of the property

## No Build System

This is a static website project with no build tools, package managers, or development dependencies. Files can be opened directly in a web browser or served via any static web server.