# Agent Instructions

## Project Overview
A static website that displays a sortable table of items loaded from a JSON file.

## Key Facts
- **Data Source**: `/data.json` contains the site content.
- **Tech Stack**: Plain HTML/JS with Bootstrap 5, jQuery, DataTables, and Lightbox2 (all via CDN).
- **Local Development**: Requires a local web server to avoid CORS issues when fetching `data.json`.
- **Security Constraints**: Strict Content Security Policy (CSP) is enforced via meta tag. Inline styles and scripts are prohibited; all custom styles must be placed in `style.css`.
